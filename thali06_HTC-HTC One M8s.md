#### Test 61703351ed386f4_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  971): Recipient 2579
--------- beginning of main
V/UserPresentBroadcastReceiver( 1780): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
E/SQLiteLog( 1885): (283) recovered 56 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
I/Scheduler( 1885): Use PeriodicScheduler
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
W/InstanceID/Rpc( 1885): Found 10024
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
I/ActivityManager(  971): Start proc com.htc.showme for broadcast com.htc.showme/.update.MobileNetworkTurnOnReceiver: pid=3083 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  971): Killing 2597:com.htc.zero:re_proc/u0a110 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=2597
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  971): Recipient 2597
D/DotMatrix( 2099): [CoverService] onDestroy, version: 1.3
I/SensorManager( 2099): unregisterListenerImpl++: listener = com.htc.dotmatrix.CoverService$7@2cf4da71
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): disable: get sensor name = CM36686 Proximity sensor
I/[AppShowMeDebug]MobileNetworkTurnOnReceiver( 3083): onReceive statefalse
W/SensorService(  971): pid=2099, uid=10041
W/SensorService(  971): Active sensors: size = 3
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  971): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.dotmatrix.CoverService$7@2cf4da71, eanble = 0, strlen(mName) = 41
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  971): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20b44e5f
W/SensorService(  971): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@39e51ce3
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 2099): [CoverService] unregisterCallContentObserver()
D/Process (  971): killProcessQuiet, pid=2099
I/ActivityManager(  971): Killing 2099:com.htc.dotmatrix/u0a41 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
I/ActivityManager(  971): Recipient 2099
I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1518): loadItems() com.htc.launcher.pageview.WidgetManager@365f55e7 +
I/Prism.WidgetManager( 1518): onLoadItems() +
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
I/Prism.ItemManager( 2435): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 2435): loadItems() com.htc.launcher.pageview.WidgetManager@8065eb7 +
I/Prism.WidgetManager( 2435): onLoadItems() +
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/Process (  971): killProcessQuiet, pid=2491
I/ActivityManager(  971): Killing 2491:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
W/ResourcesManager( 1518): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 2435): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Recipient 2491
W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
V/IccIntentReceiver( 1639): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT icc slot: 0
I/SIMStateChangeReceiver( 2041): SIM state: ABSENT
I/SIMStateChangeReceiver( 2041): remove notification
D/FlexNetS( 2041): updateSvcAllowedInSettings:false
D/ExchangePolicystatus( 2816): onReceive()
D/ExchangePolicystatus( 2816): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2816): onReceive(): else
W/ResourcesManager( 1518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/SmsReceiver( 2816): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
V/IccIntentReceiver( 1639): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
I/ActivityManager(  971): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=3109 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/ResourcesManager( 2435): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  425): Explicit concurrent mark sweep GC freed 8639(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 159us total 22.052ms
I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 140us total 16.060ms
I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 17ms
E/cutils-trace( 3105): Error opening trace file: Permission denied (13)
W/asset   ( 1518): Copying FileAsset 0x559ee27e20 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
W/asset   ( 2435): Copying FileAsset 0x559e98b2b0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
D/CustomizationManager( 3105): ====startRecUseTime====
D/htc.customization.log.level( 3105):  is 
W/CustomizationLogLevel( 3105): Level value is invalid, use default level 2
I/Prism.WidgetManager( 1518): onLoadItems() -
I/Prism.ItemManager( 1518): loadItems() com.htc.launcher.pageview.WidgetManager@365f55e7 -
I/htcbackup-core( 3109): ModelRegistry: Loading model meta data from resources...
I/Prism.WidgetManager( 2435): onLoadItems() -
I/Prism.ItemManager( 2435): loadItems() com.htc.launcher.pageview.WidgetManager@8065eb7 -
I/htcbackup-core( 3109): SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF
I/htcbackup-core( 3109): SuperSaverModeReceiver: going to send resume event
I/htcbackup-core( 3109): BackupRestoreManager: onHandleIntent
I/htcbackup-core( 3109): BackupRestoreManager: resume
D/PMS     (  971): acquireWL(144a46b1): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 971 1000 null
V/SystemUIService( 1222): BOOT_COMPLETED received
D/UsbDeviceManager(  971): boot completed
D/CustomizationManager( 3105):  Read ACC file spent 0.043 (s)
D/UsbDeviceManager(  971): [USBNET] handleMessage: 4; mConnected=true, mConfiguration=true
D/PMS     (  971): releaseWL(144a46b1): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/UsbDeviceManager(  971): [USBNET] update2: 105,0
D/UsbDeviceManager(  971): sendStickyBroadcast: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true; SetCurrentFunctions= mtp,mass_storage,adb
D/PMS     (  971): acquireWL(23103796): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 971 1000 null
D/UsbDeviceManager(  971): [USBNET] handleMessage: 105; mConnected=true, mConfiguration=true
D/PMS     (  971): releaseWL(23103796): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/CIDMapFileReader( 3105): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3105): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3105): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3105): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3105): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3105): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3105): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3105): full path : /system/customize/CID/HTC__102.xml
D/Tethering(  971): got USB_STATE change: usbConnected=true, mRndisEnabled=false, mUsbTetherRequested=false
I/CustomizationCIDLoader( 3105): Parsing tag category name = system
W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1626 com.android.server.usb.UsbDeviceManager$UsbHandler.handleMessage:1624 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:155 android.os.HandlerThread.run:61 
I/CustomizationCIDLoader( 3105): Parsing tag category name = application
I/CustomizationCIDLoader( 3105): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3105): Parsing tag category name = AutomotiveHome
D/PhoneApp( 1457): EVENT_QUERY_MO_PACKAGES
I/CustomizationCIDLoader( 3105): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3105): Parsing tag category name = Settings
I/CustomizationCIDLoader( 3105): Parsing tag category name = ACC
D/PhoneApp( 1457): -- N1 =0
I/CustomizationCIDLoader( 3105): add string-array item, value = 42507
I/CustomizationCIDLoader( 3105): add string-array item, value = 21902
I/CustomizationCIDLoader( 3105): add string-array item, value = 26006:26001.26002.26003
D/PhoneApp( 1457): -- N2 =0
I/CustomizationCIDLoader( 3105): add string-array item, value = 23420
I/CustomizationCIDLoader( 3105): add string-array item, value = 22299
I/CustomizationCIDLoader( 3105): add string-array item, value = 24002
I/CustomizationCIDLoader( 3105): add string-array item, value = 23210
I/CustomizationCIDLoader( 3105): add string-array item, value = 23205
I/CustomizationCIDLoader( 3105): add string-array item, value = 23806
I/CustomizationCIDLoader( 3105): add string-array item, value = 23430
I/CustomizationCIDLoader( 3105): add string-array item, value = 23408
I/CustomizationCIDLoader( 3105): add string-array item, value = 27205
I/CustomizationCIDLoader( 3105): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 24002:D:0:0
D/PhoneApp( 1457): -- N3 =0
I/CustomizationCIDLoader( 3105): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 23430:C:1:0
I/RecoverySystem(  971): No recovery log file
I/CustomizationCIDLoader( 3105): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 3105): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 3105):  Read CID file spent 0.088 (s)
D/CustomizationManager( 3105):  All configurations done spent 0.088 (s)
W/ResourcesManager(  971): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  971): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3156 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/UsbDeviceManager(  971): [USBNET] sendStickyBroadcast ACTION_USB_CONNECT2PC: 1
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/UsbnetService(  971): onReceive ACTION_USB_STATE: true,false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
I/ActivityManager(  971): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=3170 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
D/MountService(  971): sharing = 0 
D/MountService(  971): Unmount PCTOOL.ISO
D/VoldConnector(  971): SND -> {10 mountISO unmount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/MountService(  971): unmountISO --
I/ActivityManager(  971): Start proc com.futuredial for broadcast com.futuredial/.ui.BootCompletedReceiver: pid=3198 uid=10082 gids={50082, 9997, 3002, 3001} abi=arm64-v8a
D/PMS     (  971): acquireHCC(44a5134): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 971 1000 null
D/PMS     (  971): acquireHCC(3a9a9b5d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 971 1000 null
I/ActivityManager(  971): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 3105 on display 0
W/asset   (  971): Copying FileAsset 0x559eb9f5d0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  971): acquireWL(3838d4ff): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 971 1000 null
I/FeedHostManager( 1518): [onPause]
I/FeedProviderManager( 1518): onPause
I/FeedHostManager( 1518): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2c03b72d
I/SocialFeedProvider( 1518): +onPause
I/SocialFeedProvider( 1518): -onPause
I/AnimationUtil(  971): isHTCRecent(HelloWorld/Recent screens.)/9
I/ActivityManager(  971): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3223 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ResourcesManager( 3198): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 3198): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/BootReceiver(  971): Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
I/TrimMemoryManager( 1518): [trimMemory] 20
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  971): Copying audit failures to DropBox
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  971): Copied 0 worth of audits to DropBox
I/BootReceiver(  971): Checking for fsck errors
I/BootReceiver(  971): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  971): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  971): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
I/BootReceiver(  971): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/ActivityManager(  971): Killing 2470:com.htc.sense.socialplugins/u0a21 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=2470
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/BootReceiver(  971): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
W/asset   ( 3223): Copying FileAsset 0xac300c40 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/StatusBarManagerService(  971): setSystemUiVisibility(0x0)
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
I/DeviceManagement( 3170): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=3170 dbg=false s=true
E/ActivityThread( 1518): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1518): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1518): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1518): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1518): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1518): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1518): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1518): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/ActivityThread( 1518): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1518): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1518): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread( 1518): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/BootReceiver(  971): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  971): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  971): Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  971): Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE),
E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,E/SharedPreferencesImpl(  971): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  971): Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE),
,I/ActivityManager(  971): Recipient 2470
,I/ActivityManager(  971): Activity reported stop, but no longer stopping: ActivityRecord{13825522 u0 com.htc.launcher/.Launcher t11},
,I/[FDDMI]BootCompletedReceiver( 3198): BootCompletedReceiver :android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  971): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=3247 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
,D/PMS     (  971): acquireWL(23eed6e8): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10024},
V/AlarmManager(  971): sending alarm PendingIntent{319c6101: PendingIntentRecord{ce9cba6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=41107, Int=0
,I/DeviceManagement( 3170): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40],
,I/DeviceManagement( 3170): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
,I/DeviceManagement( 3170): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
,D/OtaStartupReceiver( 1457): onReceive: android.intent.action.BOOT_COMPLETED
,W/HtcActiveEngineManager(  971): Can't find out the target sensor
,I/DeviceManagement( 3170): WorkflowService: Starting workflow service
,E/WifiStateMachine(  971): handleMessage: E msg.what=131206
E/WifiStateMachine(  971): processMsg: InitialState
E/WifiStateMachine(  971):  InitialState CMD_BOOT_COMPLETED 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_BOOT_COMPLETED 0 0
D/ConnectivityService(  971): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  971): NetworkFactory connected
E/WifiStateMachine(  971): handleMessage: X
,D/WIFI    (  971): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/WIFI    (  971):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  971): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  971): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/UsbnetService(  971): onReceive ACTION_BOOT_COMPLETED
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/UsbnetService(  971): UsbnetHandler::handleMessage+:4
D/UsbnetService(  971): MESSAGE_BOOT_COMPLETED+
,I/DeviceManagement( 3170): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@158366a9] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 3170): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
D/UsbnetService(  971): systemReady+
D/UsbnetService(  971): systemReady-
D/UsbnetService(  971): UsbnetHandler::handleMessage-
I/DeviceManagement( 3170): ModelRegistry: Loading model meta data from resources...
I/WebViewFactory( 3223): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/usbnet  (  971): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/ConnectivityService(  971): Got NetworkFactory Messenger for usbnet
D/ConnectivityService(  971): NetworkFactory connected
D/usbnet  (  971):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
D/usbnet  (  971): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
,D/Process (  971): killProcessQuiet, pid=2435
I/ActivityManager(  971): Killing 2435:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 3170): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3170): SessionStateController: Checking invariants...
,I/ActivityManager(  971): Recipient 2435
,D/WifiService(  971): updateDevicePolicy Exchange policy allowWifiStatus = 1
,D/WifiService(  971): updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
,I/ActivityManager(  971): Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3273 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a
,D/MediaProvider( 3247): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/MediaProvider( 3247): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3247): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3247): [MP][DEBUG] Storage State: removed
,D/MediaProvider( 3247): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3247): [MP][DEBUG] Storage State: removed
I/LibraryLoader( 3223): Time to load native libraries: 11 ms (timestamps 1543-1554)
,I/LibraryLoader( 3223): Expected native library version number "",actual native library version number ""
,D/UsbReceiver( 3273): onReceiver android.intent.action.BOOT_COMPLETED
,D/HtcModeClient( 3273): power connected, start service,
E/SQLiteLog( 3247): (283) recovered 8 frames from WAL file /data/data/com.android.providers.media/databases/external.db-wal
,V/WebViewChromiumFactoryProvider( 3223): Binding Chromium to main looper Looper (main, tid 1) {29ba95c4},
I/LibraryLoader( 3223): Expected native library version number "",actual native library version number ""
,D/Utils   ( 3273): CMD:getprop ro.htc.htcmode.socket.type
,I/chromium( 3223): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/System  ( 3273): exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
I/ActivityManager(  971): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3301 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/BrowserStartupController( 3223): Initializing chromium process, singleProcess=true,
,W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3223): ApplicationContext is null in ApplicationStatus
,D/HtcModeClient( 3273): sSocketMode = LocalSocket,
,D/HtcModeClient( 3273): start the htcmodeservice thread,
D/HtcModeClient( 3273): initCanAgent
,I/CANMesgAgentLocalSocket( 3273): CANAgent Id = 0,
,W/chromium( 3223): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,D/HtcModeClient( 3273): sense info: version = none, id = 2
,V/AlarmManager(  971): sending alarm PendingIntent{3d0c1d73: PendingIntentRecord{2913c430 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=41684, Int=0
,D/HtcModeClient( 3273): display info: width = 1080, height = 1776
D/HtcModeClient( 3273): display info: mode = 10
,D/HtcModeClient( 3273): onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,D/HtcModeClient( 3273): connectState: BT_TURNON_BYME = false
,D/HtcModeClient( 3273): connectState: CONNECTION_READY = false
,W/chromium( 3223): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,D/HtcModeClient( 3273): connectState: ENABLE_PROJECTBYAPP = false
D/HtcModeClient( 3273): connectState: ENTER_PROJECTMODE = false
D/HtcModeClient( 3273): connectState: PHONE_PULGIN = false
,D/HtcModeClient( 3273): connectState: Force_AWAKE = false
D/HtcModeClient( 3273): connectState: PHONE_PULGIN = true
D/HtcModeClient( 3273): connectState: POWERCONNECTED_READY = true
,I/DeviceManagement( 3170): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/Process (  971): killProcessQuiet, pid=2621
I/ActivityManager(  971): Killing 2621:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
E/libEGL  ( 3223): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3223): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3223): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 3223): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 3223): Build Date: 03/09/15 Mon
I/Adreno-EGL( 3223): Local Branch: 
I/Adreno-EGL( 3223): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 3223): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 3223):                  d74aa161a12b9c6fc6332151
,W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17453f3a:true
,D/BluetoothAdapter( 3223): 245365619: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  971): Recipient 2621
,W/ContextImpl( 3301): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,I/DeviceManagement( 3170): SessionStateController: Checking invariants...
,I/ActivityManager(  971): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3346 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/PowerSaverNotificationService( 3301): updateNotification, mToggle = false
,I/ActivityManager(  971): Killing 2908:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=2908
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 3170): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3170): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@158366a9]
,I/ActivityManager(  971): Recipient 2908
,I/DeviceManagement( 3170): WorkflowService: Stopping workflow service
,I/ActivityManager(  971): Killing 2930:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=2930
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/ResourcesManager( 3346): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  971): Recipient 2930
,D/CalendarApplication( 3346): onCreate
,E/htcbackup-core( 3109): BackupRestoreManager: Storage is not configured
,E/htcbackup-core( 3109): BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE
,D/AlertReceiver( 3346): beginStartingService,
,D/PMS     (  971): acquireWL(2084d78d): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3346 10010 null
D/PMS     (  971): acquireWL(164aed42): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 2041 10011 null
,D/PMS     (  971): releaseWL(164aed42): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
,D/DFPI.PIReciver( 2979): onReceiver action:android.intent.action.BOOT_COMPLETED,
W/CustomizationIntentService( 1639): failed at default contact creation!
W/CustomizationIntentService( 1639): java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
W/CustomizationIntentService( 1639): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
W/CustomizationIntentService( 1639): 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
W/CustomizationIntentService( 1639): 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
W/CustomizationIntentService( 1639): 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
W/CustomizationIntentService( 1639): 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
W/CustomizationIntentService( 1639): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
W/CustomizationIntentService( 1639): 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
W/CustomizationIntentService( 1639): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/CustomizationIntentService( 1639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/CustomizationIntentService( 1639): 	at android.os.Looper.loop(Looper.java:155)
W/CustomizationIntentService( 1639): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/CustomizationIntentService( 1639): handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
D/DFPI    ( 2979): getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@2cf4da71
,W/CustomizationIntentService( 1639): AFH Enable: false, LEONCHAME: false
,D/DFPI    ( 2979): set install APK prefrence is false
,W/CustomizationIntentService( 1639): hasBeenInit true
W/CustomizationIntentService( 1639): isNewChameleonHFASupported false
W/CustomizationIntentService( 1639): isHFA true
W/CustomizationIntentService( 1639): setupWizRun 1
,D/HtcAlertService( 3346): start to updateAlertNotification!
,D/HtcAlertService( 3346): No fired or scheduled alerts
D/HtcAlertUtils( 3346): -- cancelReminderNotification --
,D/HtcAlertUtils( 3346): broadcastExistReminder!
,D/PMS     (  971): releaseWL(2084d78d): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,W/AlertReceiver( 3346): stopSelfResult true
,I/ActivityManager(  971): Killing 2952:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=2952
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  971): Explicit concurrent mark sweep GC freed 33514(2MB) AllocSpace objects, 53(3MB) LOS objects, 33% free, 15MB/23MB, paused 1.734ms total 153.035ms
,W/AwContents( 3223): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3223): CordovaWebView is running on device made by: HTC,
,W/System.err( 3109): Starting the HTTP client,
,W/htcbackup-core( 3109): BackupServiceClientResourceProxy: Reseting appServerErrorCount,
,I/ActivityManager(  971): Recipient 2952
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,I/ActivityManager(  971): Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3388 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a
,W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring,
,W/htcbackup-core( 3109): BackupRestoreManager: No sense account found - aborting,
,I/htcbackup-core( 3109): BackupRestoreManager: DM is not ready, pending resume
,I/ActivityManager(  971): Killing 1736:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=1736
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 1736
,W/chromium( 3223): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/FlexNetS( 2041): setNetMode:0, false,
,D/FlexNetS( 2041): set2gLowSignalEnablePref: false
V/FlexNetS( 2041): [DRX] setHigherPowerIn2GPref to: true
D/FlexNetS( 2041): setSimCardisWhiteList: false
V/FlexNetS( 2041): setSimCardCamp3GNetworkSignalPref to: false
,D/FlexNetS( 2041): setCampNetworkisBlackList: false
,D/FindExtension( 3223): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,V/FlexNetS( 2041): [DRX] setHigherPowerIn2GPref to: true
,V/FlexNetS( 2041): setRilHandOverW2GEnable: 0
,D/FlexNetS( 2041): updateSvcAllowedInSettings:false
,I/InputMethodManager( 3223): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2cd434de, mServedView=org.apache.cordova.engine.SystemWebView{2a56bf VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@f2f518c,
I/InputMethodManagerService(  971): Disable input method client, pid=1518
,D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/InputMethodManagerService(  971): Enable input method client, pid=3223
,W/XT9_C   ( 1353): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1353): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/BindingManager( 3223): Cannot call determinedVisibility() - never saw a connection for the pid: 3223,
I/chromium( 3223): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/ActivityManager(  971): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3424 uid=10026 gids={50026, 9997} abi=arm64-v8a
D/Process (  971): killProcessQuiet, pid=3004
I/ActivityManager(  971): Killing 3004:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/JsMessageQueue( 3223): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3223): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager(  971): Recipient 3004,
,I/ActivityManager(  971): Displayed com.example.hello/.MainActivity: +1s927ms
,D/PMS     (  971): releaseWL(3838d4ff): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  971): releaseHCC(44a5134): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  971): releaseHCC(3a9a9b5d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,V/OneTimeInitializerReceiver( 3424): OneTimeInitializerReceiver.onReceive
,V/OneTimeService( 3424): OneTimeService.onHandleIntent
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=2756, uid=10027, userID:0,
,D/jxcore_app_log( 3223): JniHelper::setJavaVM(0xab1a58f8), pthread_self() = -1405668264,
,I/ActivityManager(  971): Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3455 uid=10029 gids={50029, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=arm64-v8a
,W/jxcore-log( 3223): Initializing JXcore engine,
W/jxcore-log( 3223): JXcore engine is ready
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=2756, uid=10027, userID:0
,D/PMS     (  971): acquireWL(39f0b18f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(39f0b18f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/RlzPingService( 2756): Setting next ping for 1458201245889
,W/jxcore-log( 3223): Starting JXcore engine,
,D/PMS     (  971): acquireWL(1ce2f025): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): releaseWL(1ce2f025): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(1369b5fa): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): releaseWL(1369b5fa): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(32d0d7ab): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): releaseWL(32d0d7ab): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  971): Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3481 uid=10031 gids={50031, 9997, 3003} abi=arm64-v8a
I/ActivityManager(  971): Killing 3041:com.android.settings/1000 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3041
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/jxcore-log( 3223): Platform android
W/jxcore-log( 3223): 
W/jxcore-log( 3223): Process ARCH arm
W/jxcore-log( 3223): 
,I/jxcore-log( 3223): JXcore Cordova bridge is ready!,
I/jxcore-log( 3223): 
W/jxcore-log( 3223): JXcore engine is started
,E/jxcore  ( 3223): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js,
E/jxcore  ( 3223): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}],
,I/ActivityManager(  971): Recipient 3041
,D/PMS     (  971): acquireWL(18d37c6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): releaseWL(18d37c6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/FindExtension( 3223): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,D/PMS     (  971): acquireWL(19434387): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(19434387): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(1a112b4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(1a112b4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  971): Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  971): Killing 3083:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3083
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  425): Explicit concurrent mark sweep GC freed 8666(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 131us total 21.809ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 132us total 15.583ms,
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 118us total 15.036ms
,I/ActivityManager(  971): Recipient 3083,
,D/Process (  971): killProcessQuiet, pid=2706
I/ActivityManager(  971): Killing 2706:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 2706
,D/Process (  971): killProcessQuiet, pid=2816
I/ActivityManager(  971): Killing 2816:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 2816
,E/Personalize.BootComple_( 3503): onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) }
I/ActivityManager(  971): Killing 3109:com.htc.backup/u0a109 (adj 15): empty #17
E/Personalize.BootComple_( 3503): action android.intent.action.BOOT_COMPLETED
D/Process (  971): killProcessQuiet, pid=3109
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/Personalize.Utilities( 3503): SimpleLauncher not found: com.htc.simplelauncher
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3503, uid=1000, userID:0
,I/ActivityManager(  971): Recipient 3109
,E/Personalize.BootComple_( 3503): initialize: false
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3503, uid=1000, userID:0
,E/Personalize.Utilities( 3503): setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
,V/BootCompletedReceiver( 2791): ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,D/PeopleYouKnow( 2791): receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) },
,I/ActivityManager(  971): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3524 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,D/Process (  971): killProcessQuiet, pid=3198
I/ActivityManager(  971): Killing 3198:com.futuredial/u0a82 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 3198
,V/HtcDataRoamingWidget.DisableWidgetReceiver( 3524): ACTION_BOOT_COMPLETED,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3524, uid=10040, userID:0
,V/HtcDataStripWidget.DisableWidgetReceiver( 3524): ACTION_BOOT_COMPLETED,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3524, uid=10040, userID:0
,D/Process (  971): killProcessQuiet, pid=3156
,I/ActivityManager(  971): Killing 3156:com.android.keychain/1000 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  971): Recipient 3156
,D/DotMatrix( 1304): [EventReceiver] onReceive, version:1.3
,I/ActivityManager(  971): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3545 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/ActivityManager(  971): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=3567 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a,
,W/ResourcesManager( 3567): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Killing 3301:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3301
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 3301,
,D/MediaSessionHelper( 3567): Attempting to get helper with context android.app.ReceiverRestrictedContext@2e8e87fb,
,D/MediaSessionService(  971): Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music
,D/MediaSessionHelper( 3567): addMediaButtonListener added PendingIntent{2cf4da71: android.os.BinderProxy@27409018},
,I/ActivityManager(  971): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=3591 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 3170:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3170
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 3170
,I/ActivityManager(  971): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3613 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActivityManager(  971): Killing 3346:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3346
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 3346
,W/ContextImpl( 3613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 3613): MY_DEBUG = false
W/ContextImpl( 3613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 3613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 3613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,V/AlarmManager(  971): sending alarm PendingIntent{4692c95: PendingIntentRecord{3c9b91aa com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1457596448456, Int=0
,W/ContextImpl( 3613): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:208 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:71 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/[PluginManager]RegisterService( 1421): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
,D/HtcAppUPService( 1421): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/HtcAppUPService( 1421): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@2cd26f8f
,D/HtcAppUPService( 1421): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
,D/AutoSetting( 1421): receiver - intent: android.intent.action.BOOT_COMPLETED
,I/WSP     ( 1421): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
D/HtcAppUPService( 1421): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,I/ActivityManager(  971): Start proc com.htc.HTCSpeaker for broadcast com.htc.HTCSpeaker/.overlayui.BootReceiver: pid=3645 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
,D/HtcAppUPService( 1421): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
I/ActivityManager(  971): Killing 2979:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=2979
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	,at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61),
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/FeatureList( 1421): feature
D/FeatureList( 1421): type
D/FeatureList( 1421): description
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
,W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/B,undle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155),
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	,at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Bundle  ( 1421): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.,
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1421): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1421): Attempt to cast generated internal exception:
W/Bundle  ( 1421): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:800)
W/Bundle  ( 1421): 	at android.os.BaseBundle.getInt(BaseBundle.java:782)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source),
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1421): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1421): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1421): 	at android.os.Looper.loop(Looper.java:155)
W/Bundle  ( 1421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  971): Recipient 2979
,D/AutoSetting( 1421): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
,D/AutoSetting( 1421): service - onStartCommand() boot completed, remove cache
,D/AutoSetting( 1421): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1421): service - handleMessage() removing cache
D/AutoSetting( 1421): service - AddressCache: clean up all cache
D/AutoSetting( 1421): service - handleMessage() setting current location null
,V/BootReceiver( 3645): onReceive: android.intent.action.BOOT_COMPLETED
,D/BootReceiver( 3645): boot completed:
,D/BootReceiver( 3645): isValid:  isEnabledEasyAccess = true, isEnabledQuickDial = true,
D/BootReceiver( 3645): Valid
D/BootReceiver( 3645): startService:
,I/ActivityManager(  971): Start proc com.htc.HTCSpeaker:ngfservice for service com.htc.HTCSpeaker/.NGFService: pid=3666 uid=10054 gids={50054, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi-v7a
,D/Process (  971): killProcessQuiet, pid=3247,
I/ActivityManager(  971): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=3680 uid=10058 gids={50058, 9997, 1028, 1015, 1023} abi=arm64-v8a
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  971): Killing 3247:android.process.media/u0a17 (adj 15): empty #17
,I/ActivityManager(  971): Recipient 3247
,D/PluginProvider( 1421): Begin Apply Batch,
,E/PluginProvider( 1421): conflict when insert feature, ignored,
,D/NGFService( 3666): onCreate +++,
,D/SettingUtils( 3666): getProcessNormalFlag: true
D/NGFService( 3666): onCreate last time crash or 1st run=false
D/SettingUtils( 3666): setProcessNormalFlag: false
,D/NGFService( 3666): getAudioStreamType: ScoOn =false,
D/SoundEffects( 3666): init +++ 3
,W/LMW     ( 3680): [3711][ActionDeviceStorageHandler] onActionBootComplete++,
,W/LMW     ( 3680): [3711][ActionDeviceStorageHandler] onActionBootComplete--
,I/ActivityManager(  971): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3714 uid=10063 gids={50063, 9997, 1028, 3003} abi=arm64-v8a
,I/ActivityManager(  971): Killing 3388:com.htc.fm/u0a20 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3388
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/AudioCache(  407): Heap size overflow! req size: 1058400, max size: 1048576
,W/NuPlayerRenderer(  407): AudioSink write short frame count 0 < 9824
,I/ActivityManager(  971): Recipient 3388
,I/ActivityManager(  971): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=3771 uid=10017 gids={50017, 9997, 2001, 3003, 1028, 1015, 3007, 1023, 5001, 1024} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=2041
I/ActivityManager(  971): Killing 2041:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/NGFLanguageMgr( 3666): LanguageFromSystem: language:en  country:gb
,D/NGFLanguageMgr( 3666): language package name = preload_package
,D/PluginProvider( 1421): apply Batch success
,I/[PluginManager]RegisterService( 1421): Notify Carousel that a new TabPlugin has been installed!
,I/ActivityManager(  971): Recipient 2041
,D/MediaProvider( 3771): [MP][DEBUG] Sorting: order:0, path:/storage/emulated/0
,D/MediaProvider( 3771): [MP][DEBUG] Storage State: mounted
D/MediaProvider( 3771): [MP][DEBUG] Sorting: order:1, path:/storage/ext_sd
D/MediaProvider( 3771): [MP][DEBUG] Storage State: removed
D/MediaProvider( 3771): [MP][DEBUG] Sorting: order:2, path:/storage/usb
D/MediaProvider( 3771): [MP][DEBUG] Storage State: removed
,E/SQLiteLog( 3771): (283) recovered 8 frames from WAL file /data/user/0/com.android.providers.media/databases/external.db-wal
,I/NMT     ( 3666): NMT version: 1.6.1-B006 REL,
,D/NGFService( 3666): Audio Dump Folder: Elvis = /data/data/com.htc.HTCSpeaker/files/htcspeak_elvis, PCM = /data/data/com.htc.HTCSpeaker/files/htcspeak_pcm
,D/NGFService( 3666): applyCurrentSystemLanguage +++
,D/NGFService( 3666): grammar support language:[United States English, Taiwanese Mandarin, Chinese Mandarin, German, Latin American Spanish, European Spanish, European French, Italian, British English, Japanese, Canadian French, Chinese Cantonese, Danish, Greek, Finnish, Dutch, Norwegian, Polish, Brazilian Portuguese, European Portuguese, Russian, Swedish, Australian English, Turkish]
D/NGFLanguageMgr( 3666): LanguageFromSystem: language:en  country:gb
,D/NGFService( 3666): Elvis language uses the language: 2
D/NGFService( 3666): setCurrentNGFLanguageMgr: Language = 2, CurrentLanguage = 0
D/NGFService( 3666): setCurrentNGFLanguageMgr: set language = British English
D/NGFService( 3666): bluetoothInitialize +++
,D/MediaScannerReceiver( 3771): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
,D/MediaProviderUtils( 3771): [startScan]volume:internal, action:android.intent.action.MEDIA_MOUNTED
W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23e74068:true
,D/NGFService( 3666): cloud_init +++
D/NGFLanguageMgr( 3666): getCloudServerDNSName: language = 2, DNS name = cc.nvc.engb.nuancemobility.net
,D/MediaProviderUtils( 3771): [startScan]volume:external, action:android.intent.action.MEDIA_MOUNTED
,D/NGFService( 3666): elvisInitalize +++
,D/NGFService( 3666): elvisInitalize lang = British English
,D/NGFService( 3666): elvisInitalize: Freq Type:16000
,D/NGFService( 3666): tts_init +++
D/NGFLanguageMgr( 3666): getVocalizerFolderName: language = 2, folder name = vocalizer_eng
,D/NGFLanguageMgr( 3666): LanguageFromSystem: language:en  country:gb,
D/NGFLanguageMgr( 3666): language package name = preload_package
,D/NGFService( 3666): load vocalizer language = British English,
,E/NGFService( 3666): registerObserver
,I/art     (  971): Explicit concurrent mark sweep GC freed 13566(724KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.174ms total 122.398ms,
,D/NGFService( 3666): onCreate: Battery Level Remaining: 100%
D/NGFService( 3666): onStartCommand(): service start
,D/NGFService( 3666): onStartCommand() action = com.htc.HTCSpeaker.NGFService.QuickCall
D/NGFService( 3666): QuickCall
,W/NMT-OemFile( 3666): fopen(): Failed to open file sysdct.dat
,W/NMT-OemFile( 3666): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat,
,W/NMT-OemFile( 3666): fopen(): Failed to open file clc_eng_daniel_cfg3_bet3.dat
,W/NMT-OemFile( 3666): fopen(): Failed to open file sysdct.dat,
W/NMT-OemFile( 3666): fopen(): Failed to open file sysdct.dat
,D/NGFService( 3666): Elvis is initialization Success,
W/NMT-OemFile( 3666): fopen(): Failed to open file clm.dat
,D/NGFService( 3666): bElvisInitializeCompleted = true
D/NGFService( 3666): GrammarState = 0
D/NGFService( 3666): loadGrammar +++
D/NGFService( 3666): loadGrammar asr_grammar
I/NGFService( 3666): GrammarDepot contains a valid Elvis Grammar0
D/NGFService( 3666): loadGrammar from cache
,W/NMT     ( 3666): Fail to open read-stream for file elvisBritish Englishalbum.lst
,W/NMT     ( 3666): Fail to open read-stream for file elvisBritish Englishplaylist.lst,
W/NMT-OemFile( 3666): fopen(): Failed to open file daniel_userdct_eng.dat
,W/NMT     ( 3666): Fail to open read-stream for file generic.lst
,W/NMT     ( 3666): Fail to open read-stream for file elvisBritish Englishgeneric.lst
,W/NMT     ( 3666): Fail to open read-stream for file elvisBritish Englishname.lst
,W/NMT     ( 3666): Fail to open read-stream for file elvisBritish Englishartist.lst,
I/HtcModeClient( 3273): handler message = 4011
,E/HtcModeClient( 3273): Check connection and retry 1 times.
,W/NMT     ( 3666): Fail to open read-stream for file elvisBritish Englishsong.lst,
,D/SettingUtils( 3666): setProcessNormalFlag: true,
D/NGFService( 3666): RebuildListener constraintList size 17,
,D/NGFService( 3666): RebuildListener: onComplete0
D/NGFService( 3666): onComplete GRAMMAR_STATE_DEFAULT,
D/NGFService( 3666): switchScenario: htc_screen_140_19
,D/NGFService( 3666): Activated grammar scenario [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3666): Activated grammar constraintNames [call, play, search, help, check_message, find, cancel, exit, more]
D/NGFService( 3666): Loading grammar completed.,
D/NGFService( 3666): update contact cache completed
D/SettingUtils( 3666): set Updatge Contact Cache: false
,D/MediaScannerServiceEx( 3771): Action not in map, volume = internal, action = android.intent.action.MEDIA_MOUNTED
D/MediaScannerServiceEx( 3771): Action not in map, volume = external, action = android.intent.action.MEDIA_MOUNTED
,D/PMS     (  971): acquireWL(3c441126): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3771 10017 null
,D/MtpReceiver( 3771): [MTP][handleUsbStateAsync]+
,D/MtpReceiver( 3771): [MTP][handleUsbStateAsync]1:1-,
D/MtpReceiver( 3771): [MTP][handleUsbState]+
,I/ActivityManager(  971): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=3829 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/MediaProvider( 3771): bindService() MTP Service Connection.
,D/MtpReceiver( 3771): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3771): [MTP][handleUsbState]-
,D/MtpReceiver( 3771): [MTP][handleMessage]-
,D/MtpService( 3771): updating state; isCurrentUser=true, mMtpLocked=false,
,D/MtpService( 3771): addStorageInternal without MtpServer
,D/MediaScanner( 3771): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
,D/MtpService( 3771): [MTP][onCreate]-,
,I/ActionCombine( 3771): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/MtpService( 3771): [MTP] startForeground
E/SQLiteLog( 3771): (283) recovered 30 frames from WAL file /data/user/0/com.android.providers.media/databases/internal.db-wal
,D/MtpService( 3771): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 3771): TotalSize=1886532,MediaCacheLimit=6000
D/PMS     (  971): acquireWL(31732257): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2130 10024 null
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/MtpService( 3771): starting MTP server in MTP mode
,D/MtpService( 3771): addStorageInternal 65537 /storage/emulated/0,
,W/HtcWrapAdjustableCursorFactory( 3829): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 3829): onCreate,
,D/MtpService( 3771): [checkStorageState] Storage state - mounted,
D/MtpDatabase( 3771): [MTP][addStorage] iHostType =2
D/MtpService( 3771): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
I/RemoteViews( 1222): apply : com.android.providers.media 0 14 2 36
,V/GetPrviateResource( 3829): GetPrviateResource
,V/GetPrviateResource( 3829): GetPrviateResource
,D/MessageCustFlag( 3829): sense_version=6.0
,I/RemoteViews( 1222): apply : com.android.providers.media 0 15 1 51
,D/BTAccessoryUtil( 3829): createReceiver,
,D/BTAccessoryUtil( 3829): registerReceiver return intent = null
,D/MessageCustFlag( 3829): sku_id=118
,D/HtcBuildUtils( 3829): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3829): Cannot find qct_8960_interface, use default value instead
,V/MmsSystemEventReceiver( 3829): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) },
,D/ExchangePolicystatus( 3829): onReceive()
D/ExchangePolicystatus( 3829): onReceive(): ACTION_BOOT_COMPLETED
,D/MessageUtils( 3829): Text messaging allow status = allow,
D/Messaging( 3829): EAS allow SMS !!!
D/ExchangePolicystatus( 3829): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 3829): EAS allow SMS !!!
,I/ActivityManager(  971): Start proc com.htc.cs.pns for broadcast com.htc.cs.pns/.receiver.BootCompletedReceiver: pid=3866 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,D/PMS     (  971): acquireWL(131243ae): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 3829 10064 null,
,V/SmsReceiverService( 3829): onStart: #1, @360933033
,V/SmsReceiverService( 3829): action: android.intent.action.BOOT_COMPLETED
,D/SmsReceiverService( 3829): isCbm: false
D/SmsReceiverService( 3829): isDiscard: false
,W/MediaScanner( 3771): Error opening directory '/oem/media/', skipping: No such file or directory.
,D/SettingsManager( 3829): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@37abacad
,I/art     (  427): Explicit concurrent mark sweep GC freed 8692(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 370us total 23.465ms,
,I/iu.UploadsManager( 2130): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
V/SmsReceiverService( 3829): handleBootCompleted
W/MediaScanner( 3771): Error opening directory '/oem/media/', skipping: No such file or directory.
,E/MediaScannerService( 3771): [handleMessage] --- Should not be here, ignore request. ----
D/MediaScanner( 3771):  prescan time: 136ms
D/MediaScanner( 3771):     scan time: 37ms
D/MediaScanner( 3771): postscan time: 0ms
D/MediaScanner( 3771):    total time: 173ms
D/MediaScanner( 3771): -----------------------------------------------------------------
D/MediaScanner( 3771): firstscan(media) time: 23ms
D/MediaScanner( 3771): secondscan(non-media) time: 9ms
D/MediaScanner( 3771):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Total]    File(Image+Video+Audio+Others) in database : 339
E/MediaScannerService( 3771): [onStartCommand] --- Should not be here, redirect request. ----
,W/ResourcesManager( 3829): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  427): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 243us total 16.073ms
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1457): sku_id=118
,I/art     (  427): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 225us total 14.587ms
,D/SmsReceiverService( 3829): OutBoxSize = 0,
D/SmsReceiverService( 3829): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 3829): sku_id=118
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/AccFlag ( 1457): sku_id=118
,D/MessageCustFlag( 3829): sku_id=118,
,D/SmsReceiverService( 3829): sendFirstQueuedMessage end cnt> 0
,D/SpaceBufferUtil( 3829): > createBufferFile()
D/SpaceBufferUtil( 3829): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
D/SpaceBufferUtil( 3829): < createBufferFile()
,I/iu.UploadsManager( 2130): End new media; added: 0, uploading: 0, time: 57 ms,
,D/PMS     (  971): releaseWL(31732257): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/MediaProvider( 3771): [delete][84],
,D/MediaProvider( 3771): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3771): [recoverParentNodes] - 0
D/MediaProvider( 3771): [update][17]
D/MediaScannerServiceEx( 3771): [scan] Recover Parent Node is finished!
,E/MediaScannerServiceEx( 3771): [getStorageMaskIdFromPath] path is null
,D/PMS     (  971): releaseWL(3c441126): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3771): [ServiceHandler][handleMessage] , action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3771): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3771): [AliveExtStorageRows]+65537, 11223344
,E/cutils-trace( 3892): Error opening trace file: Permission denied (13),
I/dex2oat ( 3892): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 3892): dex2oat: override thread count:4
,D/MediaProvider( 3771): [update][7]#0#
,D/MediaProvider( 3771): [update][6]#0#
,V/AlarmManager(  971): sending alarm PendingIntent{132c84dc: PendingIntentRecord{1897c9e5 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=47113, Int=0,
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3771): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 3771): [update][10]#1#
,D/MediaScannerServiceEx( 3771): [AliveExtStorageRows]-0, 0,
,D/PMS     (  971): acquireWL(442ecba): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3771 10017 null,
,D/MediaScanner( 3771): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,I/ActivityManager(  971): Killing 3424:com.google.android.onetimeinitializer/u0a26 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3424
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 3424,
,I/dex2oat ( 3892): dex2oat took 658.399ms (threads: 4),
,I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): Htc_DEBUG_flag:          false,
I/PushClient( 3866): ApplicationMonitor {1f0642e}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/ActivityManager(  971): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3899 uid=10076 gids={50076, 9997} abi=arm64-v8a,
,I/PushClient( 3866): String {2b182068}: handleBroadcast(): Schedule update on boot completed.
,D/SMSBackup( 3899): Got ACTION_BOOT_COMPLETED event
D/SMSBackup( 3899): setCheckAlarm
,D/SMSBackup( 3899): Next check is scheduled at 60s from now,
,I/ActivityManager(  971): Killing 3455:com.htc.video/u0a29 (adj 15): empty #17
,D/Process (  971): killProcessQuiet, pid=3455
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  971): Recipient 3455,
,D/Process (  971): killProcessQuiet, pid=2756
,I/ActivityManager(  971): Killing 2756:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 2756
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1457, uid=1001, userID:0
I/ActivityManager(  971): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=3923 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/[AppShowMeDebug]BootCompletedReceiver( 3923): received boot complete
,I/[AppShowMeDebug]BootCompletedReceiver( 3923): push flag is false, skip check
,I/ActivityManager(  971): Start proc com.htc.feedback for broadcast com.htc.feedback/.reportagent.receiver.PolicyReceiver: pid=3946 uid=10083 gids={50083, 9997, 1007, 3003, 1028} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=3481
I/ActivityManager(  971): Killing 3481:com.htc.csrecommend/u0a31 (adj 15): empty #17,
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/MediaScanner( 3771):  prescan time: 642ms,
D/MediaScanner( 3771):     scan time: 602ms
D/MediaScanner( 3771): postscan time: 2ms
D/MediaScanner( 3771):    total time: 1246ms
D/MediaScanner( 3771): -----------------------------------------------------------------
D/MediaScanner( 3771): firstscan(media) time: 328ms
,D/MediaScanner( 3771): secondscan(non-media) time: 274ms
D/MediaScanner( 3771):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3771): [delete][12],
D/MediaProvider( 3771): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3771): [recoverParentNodes] - 0
,D/MediaProvider( 3771): [update][5]
D/MediaScannerServiceEx( 3771): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3771): [updateImage]+
,I/ActivityManager(  971): Recipient 3481,
,D/MediaScannerServiceEx( 3771): [updateImage]-0,
,D/PMS     (  971): releaseWL(442ecba): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3771): [2] scan finished
D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3771): Process mounted intent for unmounted storage: /storage/ext_sd
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]+131073,
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3771): [update][7]#1#
,D/MediaProvider( 3771): [update][23]#0#
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3771): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]+196609
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3771): [update][5]#1#
,D/MyReportAgent( 3946): PolicyReceiver  receieve: android.intent.action.BOOT_COMPLETED
,D/MyReportAgent( 3946): DatabaseHelper [DatabaseHelper constructor],
D/MyReportAgent( 3946): PolicyStore [Init] Get cached policy bundle
,I/ActivityManager(  971): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3968 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
D/MediaProvider( 3771): [update][32]#0#
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]--1, 0
,E/MediaScannerServiceEx( 3771): [getStorageMaskIdFromPath] path is null,
D/MediaScannerServiceEx( 3771): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3771): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3771): [AliveExtStorageRows]+65537, 11223344
D/MyReportAgent( 3946): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
,D/MediaProvider( 3771): [update][6]#0#
,D/MediaProvider( 3771): [update][2]#0#
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3771): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3771): [update][8]#1#
,D/MyReportAgent( 3946): ReportServiceHandler on boot complete event 
D/MediaScannerServiceEx( 3771): [AliveExtStorageRows]-0, 0
,D/PMS     (  971): acquireWL(273e509d): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3771 10017 null
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.htc.feedback, clsName=com.htc.feedback.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=3946, uid=10083, userID:0
,V/MyReportAgent( 3946): ReportServiceHandler unregister the PowerConnected Listener
,D/MediaScanner( 3771): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1,
,D/Process (  971): killProcessQuiet, pid=3503
I/ActivityManager(  971): Killing 3503:com.htc.home.personalize/1000 (adj 15): empty #17,
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 3503
,D/UpdaterAPK | UpdaterBootCompleteReceiver( 3968): onReceive() - start htcCheckinService,
,I/HtcModeClient( 3273): handler message = 4009
,I/HtcModeClient( 3273): start to setup the connection
,I/htcCheckinService(  971): htcCheckinProvider V2.1
,D/htcCheckinService(  971): htcCheckinService() the mIsServiceRunning = true
,I/htcCheckinService(  971): Checkin service onCreate()!
,I/ActivityManager(  971): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3993 uid=10090 gids={50090, 9997, 1028} abi=arm64-v8a,
,D/htcCheckinService(  971): onStartCommand()
D/htcCheckinService(  971): onStartCommand() the action name = null
I/ActivityManager(  971): Killing 2172:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/htcCheckinService(  971): InitThread start
D/Process (  971): killProcessQuiet, pid=2172
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  425): Explicit concurrent mark sweep GC freed 8626(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 201us total 27.946ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 142us total 19.405ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 160us total 19.614ms,
,I/ActivityManager(  971): Recipient 2172,
,D/Messaging( 3829): supportCMAS(SIE)/init? false/true
,D/MmsConfig( 3829): networkCode: 
,D/MmsConfig( 3829): SIE smsPri: null
,D/MmsConfig( 3829): networkCode: 
,D/MmsConfig( 3829): packageName: com.htc.vvm.att does not exist
,D/Messaging( 3829): mNeedToUpdateDate2 start,
D/ReportIndicatorCache( 3829): startAsyncQueryReports ---,
D/MmsAsyncWorkHandler( 3829): ,
D/MmsAsyncWorkHandler( 3829): HM tk = 20001
D/ReportIndicatorCache( 3829): MSG_QUERY_REPORTS >>
D/DraftCache( 3829): [DraftCache/1] DraftCache.constructor
D/DraftCache( 3829): [DraftCache/1] refresh
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
,D/AccFlag ( 1457): sku_id=118
,D/MmsConfig( 3829): networkCode: 
,I/Messaging( 3829): mccmnc> 
,D/DraftCache( 3829): [DraftCache/91] rebuildCache
,D/Messaging( 3829): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 3829): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 3829): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3829): createReceiver
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91,
D/Jerry   ( 1457): URI_DRAFT
,D/MessageCustFlag( 3829): sense_version=6.0
D/Jerry   ( 3829): start to preload cursor >>>>>>>
,D/DraftCache( 3829): hasDraft() = false mNeedNotifyChange = true
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/DraftCache( 3829): [DraftCache/91] rebuildCache time: 13
,D/TelephUtils( 1457): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
V/MmsProvider( 1457): Update uri=content://mms, match=0
V/MmsProvider( 1457): selection=st=129 AND m_type!=134
D/MmsAsyncWorkHandler( 3829): 
D/MmsAsyncWorkHandler( 3829): HM tk = 20002
,D/Messaging( 3829): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
,D/MmsSmsV2Provider( 1457):  slotId = -1000
,D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 3829): Reset downloading state: 0
V/MmsSystemEventReceiver( 3829): TransactionService is going to be woken up.
,D/Messaging( 3829): mNeedToUpdateDate2: false
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 93
D/MmsSmsV2Provider( 1457):  slotId = -1000
,V/TransactionService( 3829): 1-Creating TransactionService
,V/TransactionService( 3829): onStartCommand: 1
D/MmsSystemEventReceiver( 3829): unRegisterForConnectionStateChanges
,V/TransactionService( 3829): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3829): Loading previous transactions.
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1457): sku_id=118
,D/Messaging( 3829): ViewCache CreatePreload
D/Messaging( 3829): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 3829): _has_set_default_values_2=true,
,D/PMS     (  971): acquireWL(332d434): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3993 10090 null
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1457): sku_id=118
D/MsgPreferenceUtils( 3829): def_index: 0
,D/MsgPreferenceUtils( 3829): globalIndex = 1,
,D/MsgPreferenceUtils( 3829): phone state: true
D/MsgPreferenceUtils( 3829): sd state: false
D/MsgPreferenceUtils( 3829): vIndex = 0
,I/WorldClock.Global( 3993): isHEPDevice = true
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl(  971): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
,W/SystemReader( 3993): Cannot find support_china_sense_feature, use default value instead
,I/ActivityManager(  971): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4040 uid=10098 gids={50098, 9997, 3003} abi=arm64-v8a
,I/WorldClock.AlarmUtils( 3993): saveSupportOffAlarmInPreference: isSupport = false
,I/WorldClock.AlarmService( 3993): isDeviceEncryptionEnabled = false,
,D/PMS     (  971): releaseWL(332d434): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,D/Process (  971): killProcessQuiet, pid=2791,
I/ActivityManager(  971): Killing 2791:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/WorldClock.AlarmService( 3993): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException: Attempt to invoke virtual method 'int java.util.ArrayList.size()' on a null object reference
I/WorldClock.AlarmUtils( 3993): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,D/AutoSetting( 1421): service - mRequestRunnable: screen on delay 10s, request NLP now,
,D/AutoSetting( 1421): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1421): service - requestNLP() NetworkLocationProvider not enabled
,I/art     (  971): Explicit concurrent mark sweep GC freed 15589(750KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.503ms total 164.436ms
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1457): device_type: 1
,I/ActivityManager(  971): Recipient 2791
,D/TransactionService( 3829): Force clearing mTransactionList
,D/TransactionService( 3829): Force set service start id to 1
,V/TransactionService( 3829): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3829): unRegisterForConnectionStateChanges
I/WorldClock.AlarmUtils( 3993): Cancel any alarm from alarm manager
D/TransactionService( 3829): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 3829): Destroying TransactionService
I/WorldClock.AlarmUtils( 3993): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1222): receive(android.intent.action.ALARM_CHANGED,1,false)
V/TransactionService( 3829): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,I/WorldClock.AlarmUtils( 3993): isDeviceEncryptionEnabled = false
,I/WorldClock.AlarmUtils( 3993): Calculate next off alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmService( 3993): resetStopwatchToDefault
,I/WorldClock.DmdCmd( 3993): This version is general off mode alarm function,
W/WorldClock.DmdCmd( 3993): Conn: fail e = java.io.IOException: No such file or directory
,E/UpdateRequestReceiver( 4040): ignoring update request
,E/UpdateRequestReceiver( 4040): ignoring update request
,I/WorldClock.AlarmService( 3993): resetTimerToDefault
,E/UpdateRequestReceiver( 4040): ignoring update request
,E/UpdateRequestReceiver( 4040): ignoring update request,
,E/UpdateRequestReceiver( 4040): ignoring update request
,E/UpdateRequestReceiver( 4040): ignoring update request,
,I/ActivityManager(  971): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=4080 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
D/Process (  971): killProcessQuiet, pid=3524
I/ActivityManager(  971): Killing 3524:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 3524,
,I/DeviceManagement( 4080): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4080 dbg=false s=true
,I/DeviceManagement( 4080): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,I/DeviceManagement( 4080): WorkflowService: Starting workflow service,
,I/DeviceManagement( 4080): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@e9ffb73] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 4080): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 4080): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 4080): BootCompletedWorkflow: ==================================================
,I/DeviceManagement( 4080): ModelRegistry: Loading model meta data from resources...
,I/GoogleHttpClient( 1885): GMS http client unavailable, use old client,
,I/ActivityManager(  971): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=4104 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/DeviceManagement( 4080): BackgroundController: *** Update after boot...,
I/DeviceManagement( 4080): SessionStateController: Checking invariants...
,I/htcbackup-core( 4104): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 4080): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
,I/DeviceManagement( 4080): ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
,I/DeviceManagement( 4080): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]],
,I/ActivityManager(  971): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4134 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/DeviceManagement( 4080): BackgroundController: Invariants are unchanged.
,I/ActionCombine( 4104): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
I/DeviceManagement( 4080): SessionStateController: Checking invariants...
,V/SmsReceiverService( 3829): updateNotificationAndShortcutStatus: 
D/MessagingNotification( 3829): New incoming message, can't cancel notification now
D/MessagingNotification( 3829): newMsgCnt: 0, false
,D/MediaScanner( 3771):  prescan time: 283ms
D/MediaScanner( 3771):     scan time: 1060ms
D/MediaScanner( 3771): postscan time: 173ms
,D/MediaScanner( 3771):    total time: 1516ms
D/MediaScanner( 3771): -----------------------------------------------------------------
D/MediaScanner( 3771): firstscan(media) time: 629ms
D/MediaScanner( 3771): secondscan(non-media) time: 431ms
D/MediaScanner( 3771):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/Process (  971): killProcessQuiet, pid=3545,
I/ActivityManager(  971): Killing 3545:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3771): [delete][26]
D/MediaProvider( 3771): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289),
,D/MediaProvider( 3771): [recoverParentNodes] - 0
D/MediaProvider( 3771): [update][7]
D/MediaScannerServiceEx( 3771): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3771): [updateImage]+
,I/ActionCombine( 1304): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true,
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,D/MediaScannerServiceEx( 3771): [updateImage]-0
,I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145),
,I/DeviceManagement( 4080): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/RemoteViews( 1222): apply : com.htc.backup 4 12 5 38
I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145),
,I/RemoteViews( 1222): apply : com.htc.backup 0 4 3 5
,I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1222): apply : com.htc.backup 1 1 9 5,
I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1222): apply : com.htc.backup 0 2 1 5
I/RemoteViews( 1222): apply : com.htc.backup 1 10 25 50
,I/ActivityManager(  971): Recipient 3545,
,D/PMS     (  971): releaseWL(131243ae): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,D/PMS     (  971): releaseWL(273e509d): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 3771): [3] scan finished
,I/DeviceManagement( 4080): Perf: *** Cache update - start...
D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3771): Process mounted intent for unmounted storage: /storage/ext_sd
I/DeviceManagement( 4080): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 4080): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4080): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 4080): Perf: Scan enabled apps - start...
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 3771): [update][8]#1#
,I/ActivityManager(  971): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=4161 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
I/ActivityManager(  971): Killing 3567:com.htc.music:mediaplaybackservice/u0a48 (adj 15): empty #17,
D/Process (  971): killProcessQuiet, pid=3567
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/MediaProvider( 3771): [update][22]#0#
D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]--1, 0
,I/DeviceManagement( 4080): EnabledAppBuilder: Examining 270 installed apps for DM enabled apps...
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=649500100, versionName=6.5.853822
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031464, versionName=6.3.860159
,I/ActivityManager(  971): Recipient 3567
,D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0,
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3771): Process mounted intent for unmounted storage: /storage/usb
D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]+196609
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=444607021, versionName=4.2.857167
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 3771): [update][10]#1#
,D/ResetNotifyBootCompleteReceiver( 1457): userSerialNumber = 0,
D/ResetNotifyBootCompleteReceiver( 1457): Receive bootcomplete intent
D/ResetNotifyBootCompleteReceiver( 1457): isOwnerUser = true
,D/MediaProvider( 3771): [update][31]#0#,
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  971): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=4185 uid=10155 gids={50155, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/HtcCupdXmlParser( 4161): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,D/ActivityThread( 4161): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,W/ResourcesManager( 4080): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658011289, versionName=7.00.515351
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4080): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4080): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/HtcCupdXmlParser( 4161): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.identity, versionKey=887a7f5610a36712ed50f1fb1911e4b5da8368ea, versionCode=658001316, versionName=6.5.860193
,D/QXDM2SD:HtcNative( 1457): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true,
,I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=4208 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,W/ResourceType( 4080): ResTable_typeSpec entry count inconsistent: given 2, previously 1426,
,I/AlarmManager(  971): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED,
I/AlarmManager(  971): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  971): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  971): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=4230 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=3591
I/ActivityManager(  971): Killing 3591:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 4208): -onCreate()
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pns, versionKey=55580870d4ecef7adc0bfac442bc01d880550489, versionCode=148001224, versionName=1.2.853019
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  971): Recipient 3591
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=240000080, versionName=2.0.837715
,V/Settings:HtcSettingsApplication( 4208): [4208/4208] onCreate()
,W/ResourcesManager( 4080): Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/art     ( 3666): Suspending all threads took: 12.055ms
,I/AlarmManager(  971): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@1460ec83
W/ContextImpl( 4208): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  971): Start proc com.android.settings:remote for service com.android.settings/.framework.app.HtcIntentService: pid=4251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/AlarmManager(  971): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@25a6ce00
,I/AlarmManager(  971): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@2ec9e639
,D/TetherSettings( 4208): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.google.android.apps.maps
D/        ( 4208): Cust_ConnectToPC   : Internet_Sharing>true
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.google.android.gsf
D/        ( 4208): Cust_ConnectToPC   : Modem_Link>false
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.google.android.location
D/        ( 4208): Cust_ConnectToPC   : spcsc>false
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  971): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  971): [AlarmQueuing] add queuing package: com.facebook.orca
D/        ( 4208): Cust_ConnectToPC   : IPT>true
I/AlarmManager(  971): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
D/        ( 4208): Cust_ConnectToPC   : Singel_USB>false
I/AlarmManager(  971): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  971): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  971): Killing 3613:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3613
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/Settings( 4208): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4080): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/DeviceManagement( 4080): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=250001208, versionName=2.2.848686
,I/DeviceManagement( 4080): EnabledAppBuilder: Found 8 DM enabled apps.,
I/ActivityManager(  971): Recipient 3613
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs,
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
E/SmartNS_Utility( 4208): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4208): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4208): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/SmartNS_Utility( 4208): setISNotification
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.identity
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pns
,V/Settings:HtcSettingsApplication( 4251): [4251/4251] onCreate()
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,D/SmartNS_Utility( 4208): usb_cable_connect = 1,
D/SmartNS_Utility( 4208): usb_denied = 0,
,I/DeviceManagement( 4080): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm,
,I/SmartNS_PSService( 4208): usb notificaiton:true
,E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
,I/DeviceManagement( 4080): Perf: Scan enabled apps - complete: 1101 ms
I/DeviceManagement( 4080): Perf: *** Enabled app cache update - complete: 1102 ms
I/DeviceManagement( 4080): Perf: *** Config cache update - start...
,I/DeviceManagement( 4080): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 4080): ConfigCacheController: *** Updating stale config cache entries...
,I/ActionCombine( 4208): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 4208): usb_cable_connect = 1
,D/SmartNS_Utility( 4208): usb_denied = 0
I/SmartNS_PSService( 4208): usb notificaiton:true
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  971): Killing 3645:com.htc.HTCSpeaker/u0a54 (adj 15): empty #17
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/Process (  971): killProcessQuiet, pid=3645,
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/RemoteViews( 1222): setHTCTheme(com.android.settings,true,33751145)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): apply : com.android.settings 0 12 2 36
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,I/art     ( 4080): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>,
I/art     ( 4080): Rejecting re-init on previously-failed class java.lang.Class<org.restlet.engine.connector.HttpServerHelper$1>
,W/System.err( 4080): Starting the internal HTTP client,
,I/DeviceManagement( 4080): ConfigCacheController: Getting config update from server: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs/versions/c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17/cid/MDoxOjIwMTQtMDEtMDlUMDQ6MTI6MjQuMjMxWg
,I/ActivityManager(  971): Recipient 3645
,I/DeviceManagement( 4080): DeviceClientResource: Active network...
I/DeviceManagement( 4080):   No active network
,I/DeviceManagement( 4080): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
,I/DeviceManagement( 4080): BackgroundController: *** Network unavailable!
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=4080, uid=10099, userID:0
,I/DeviceManagement( 4080): Perf: *** Config cache update - complete: 179 ms
I/DeviceManagement( 4080): Perf: *** Cache update - complete: 1283 ms
I/DeviceManagement( 4080): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@e9ffb73]
,D/Process (  971): killProcessQuiet, pid=3680
I/ActivityManager(  971): Killing 3680:com.htc.lmw/u0a58 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/DeviceManagement( 4080): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@349ba61a] args=[Bundle[mParcelledData.dataSize=132]]
I/DeviceManagement( 4080): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
I/DeviceManagement( 4080): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 4080): SessionStateController: Checking invariants...
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
,I/HtcModeClient( 3273): handler message = 4011,
,E/HtcModeClient( 3273): Check connection and retry 2 times.,
,I/DeviceManagement( 4080): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/ActivityManager(  971): Recipient 3680,
,I/DeviceManagement( 4080): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@349ba61a],
,I/ActivityManager(  971): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4276 uid=9987 gids={49987, 9997} abi=arm64-v8a
I/DeviceManagement( 4080): WorkflowService: Stopping workflow service
,I/ActivityManager(  971): Killing 3714:com.android.managedprovisioning/u0a63 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3714
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/SmartDim(  971): Init customizeScreenOffDelayClass error
,I/ActivityManager(  971): Recipient 3714
,I/SensorManager(  971): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2aaaca2c, sensor = {Sensor name="Accelerometer Sensor", vendor="hTC Corp.", version=1, type=1, maxRange=39.2266, resolution=0.01, power=0.17, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): enable: get sensor name = Accelerometer Sensor
,W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 3
,W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  971): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaaca2c, eanble = 1, strlen(mName) = 36
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  971): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20b44e5f
W/SensorService(  971): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@39e51ce3
W/SensorService(  971): Listener[2] = com.htc.smartdim.sensor_eye@2aaaca2c
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  971): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@2aaaca2c, sensor = {Sensor name="CM36686 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): enable: get sensor name = CM36686 Proximity sensor
W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 4
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  971): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaaca2c, eanble = 1, strlen(mName) = 36,
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  971): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20b44e5f
W/SensorService(  971): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@39e51ce3
W/SensorService(  971): Listener[2] = com.htc.smartdim.sensor_eye@2aaaca2c
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/BroadcastQueue(  971): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{b105d18 u0 ReceiverList{35b968fb 971 system/1000/u0 local:195f7a8a}}
,I/htcbackup-core( 4104): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.11.05 at 12:06:52.457 CET] interval end=[2015.11.12 at 12:06:52.457 CET]
,V/AlarmManager(  971): sending alarm PendingIntent{2f3a32c4: PendingIntentRecord{1ed785ad com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=17, w=1447326412457, Int=604800000
,I/SensorManager(  971): dispatchSensorEvent: Proximity = 9.0, mListener = com.htc.smartdim.sensor_eye@2aaaca2c
,I/ActivityManager(  971): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=4300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/Process (  971): killProcessQuiet, pid=2130
I/ActivityManager(  971): Killing 2130:com.google.android.gms/u0a24 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  425): Explicit concurrent mark sweep GC freed 8692(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 293us total 25.449ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 150us total 19.465ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 148us total 18.634ms
,I/ActivityManager(  971): Recipient 2130
,I/ActivityManager(  971): Waited long enough for: ServiceRecord{33d3f571 u0 com.google.android.gms/.gcm.GcmService}
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.htc.backup does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.htc.backup 4 38
,I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1222): apply : com.htc.backup 0 2 0 5
,I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1222): apply : com.htc.backup 1 1 1 5,
I/RemoteViews( 1222): setHTCTheme(com.htc.backup,true,33751145)
,I/RemoteViews( 1222): apply : com.htc.backup 1 1 0 5
,I/RemoteViews( 1222): reapply : com.htc.backup 11 50
,I/art     (  971): Explicit concurrent mark sweep GC freed 12361(613KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.410ms total 157.900ms,
,I/ActivityManager(  971): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4323 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=2840
,I/ActivityManager(  971): Killing 2840:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 2840
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4323, uid=10072, userID:0
,W/global  ( 4323): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4323): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/global  ( 4323): [apache-http] Connection GC has been deprecated!
,W/global  ( 4323): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 4323): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  971): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=4360 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 4323): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4323): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/ResourcesManager( 4360): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4360): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4323, uid=10072, userID:0,
,I/MultiDex( 4360): VM with version 2.1.0 has multidex support
,I/MultiDex( 4360): install
I/MultiDex( 4360): VM has multidex support, MultiDex support library is disabled.,
,D/Volley  ( 4323): [405] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4323): [399] DiskBasedCache.clear: Cache cleared.
,V/JNIHelp ( 4360): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  971): Start proc com.google.android.gms for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver: pid=4384 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=3866
I/ActivityManager(  971): Killing 3866:com.htc.cs.pns/u0a71 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ActivityThread( 4360): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4360): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@191f7a3e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4360): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  971): Recipient 3866
,D/Finsky  ( 4323): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4323): [1] 2.run: Finished loading 1 libraries.
,W/ResourcesManager( 4384): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4384): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4323): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 4384): VM with version 2.1.0 has multidex support,
I/MultiDex( 4384): install
,I/MultiDex( 4384): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4323): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 4384): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 4384): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4384): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18d76a4c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4384): Installed default security provider GmsCore_OpenSSL
,D/Process (  971): killProcessQuiet, pid=3899,
I/ActivityManager(  971): Killing 3899:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  971): Recipient 3899
,V/GLSUser ( 1885): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/PMS     (  971): acquireWL(15a705ea): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1885 10024 null
,V/GmsCoreStatsServiceLauncher( 4384): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) },
,I/NotificationStore( 1885): System rebooted after Notification storage file was last written
,I/NotificationStore( 1885): Deleting the file
,D/PMS     (  971): releaseWL(15a705ea): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,V/Finsky  ( 4323): [1] GearheadStateMonitor.onReady: sIsProjecting:false
D/Process (  971): killProcessQuiet, pid=3923
I/ActivityManager(  971): Killing 3923:com.htc.showme/u0a81 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  971): Recipient 3923
,D/PersistentNotificationBroadcastReceiver( 1885): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/InstanceID/Rpc( 4384): Found 10024
,D/FileApkUtils( 4384): Spent 22ms computing apk sha1.
,D/FileApkUtils( 4384): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 4384): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm64/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-dd5b1d6850a09abe29b143730d133d3d1f4c4971@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 4384): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4384): Keeping up-to-date module: module-dd5b1d6850a09abe29b143730d133d3d1f4c4971,
,D/GmsModuleFndr( 4384): Beginning GMS chimera module scan,
,D/PMS     (  971): acquireWL(7ae6324): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 4384 10024 null
,W/asset   ( 4384): Copying FileAsset 0x559e841860 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-dd5b1d6850a09abe29b143730d133d3d1f4c4971/MapsModule.apk:/resources.arsc) to buffer size 364264 to make it aligned.
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.nearby.sharing.sharesheet.ShareActivity, state=2, flag=1, pid=1885, uid=10024, userID:0
,D/PMS     (  971): acquireWL(394d5e8d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
D/GmsModuleFndr( 4384): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/ChimeraCfgMgr( 4384): Beginning module configuration check
,D/ChimeraCfgMgr( 4384): Module APKs unchanged, check complete,
,D/PMS     (  971): acquireWL(eb2b053): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 4384 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(1d5ec68e): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(1adfeaf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4384 10024 null
,D/GCM     ( 4384): COMPAT: Multi user not supported,
,I/ActivityManager(  971): Delay finish: com.google.android.gms/.tron.AlarmReceiver
,D/GCM     ( 1885): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/PMS     (  971): acquireWL(2e65d6cb): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(394d5e8d): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(7ae6324): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  971): releaseWL(1d5ec68e): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 4384): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}],
,I/CheckinService( 4384): Disabling old GoogleServicesFramework version
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4384, uid=10024, userID:0
,D/PMS     (  971): acquireWL(1fe11966): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4384): onCreate
,I/GCoreUlr( 1780): DispatchingService.onCreate(),
,D/SystemUpdateService( 4384): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/PMS     (  971): acquireWL(2a74e1d8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=4384, uid=10024, userID:0
I/ConfigFetchService( 4384): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=4384, uid=10024, userID:0
I/ConfigService( 1885): onCreate
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/CheckinService( 4384): Checking schedule, now: 1457596457627 next: 1456765623471
I/CheckinService( 4384): active receiver: enabled
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
,W/art     ( 4384): Suspending all threads took: 5.454ms,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=4384, uid=10024, userID:0
,I/SystemUpdateService( 4384): cancelUpdate (empty URL)
I/art     ( 4384): Background sticky concurrent mark sweep GC freed 33(2656B) AllocSpace objects, 0(0B) LOS objects, 3% free, 3MB/4MB, paused 7.902ms total 17.037ms
I/SystemUpdateService( 4384): active receiver: disabled
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=4384, uid=10024, userID:0
V/AuthZen ( 4384): Handling intent: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1780): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 4384): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4384, uid=10024, userID:0
,I/art     ( 4384): Background sticky concurrent mark sweep GC freed 146(8KB) AllocSpace objects, 0(0B) LOS objects, 1% free, 4MB/4MB, paused 6.193ms total 23.289ms
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=4384, uid=10024, userID:0
,D/PMS     (  971): acquireWL(3294d725): PARTIAL_WAKE_LOCK  Icing 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
,I/ConfigFetchService( 4384): service connected,
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1780, uid=10024, userID:0
,D/PMS     (  971): releaseWL(eb2b053): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1780): Explicit concurrent mark sweep GC freed 22549(1356KB) AllocSpace objects, 4(80KB) LOS objects, 47% free, 4MB/8MB, paused 2.251ms total 63.759ms
,W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
D/PMS     (  971): releaseWL(3294d725): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ce942c6:true
,I/art     ( 4384): Background sticky concurrent mark sweep GC freed 856(80KB) AllocSpace objects, 2(40KB) LOS objects, 0% free, 4MB/4MB, paused 5.803ms total 43.580ms
,D/PMS     (  971): releaseWL(2e65d6cb): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
,D/SystemUpdateService( 4384): onDestroy
W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,D/ConfigFetchService( 4384): ConfigApi connection successful.
,I/art     ( 1885): Explicit concurrent mark sweep GC freed 6457(391KB) AllocSpace objects, 6(120KB) LOS objects, 51% free, 3MB/7MB, paused 1.062ms total 39.895ms
,I/ActivityManager(  971): Resuming delayed broadcast
,I/GLSUser ( 4384): [ChannelManager] Attempting to channel bind connection HttpClient.
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 4384): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
D/PMS     (  971): releaseWL(1fe11966): PARTIAL_WAKE_LOCK  copresGcore_EventLoop 0x1 WorkSource{10024 com.google.android.gms}
,I/Kids    ( 4384): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4483 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/GCoreUlr( 1780): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/PMS     (  971): acquireWL(343a6813): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(343a6813): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1780): Unbound from all location providers
,D/PMS     (  971): releaseWL(2a74e1d8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 WorkSource{10024 com.google.android.gms}
,I/GLSActivity( 1885): [ac] getting account id
I/AuthZen ( 4384): Fetching signing key...
,I/AuthZen ( 4384): Signing key fetched successfully!,
,W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,W/ResourcesManager( 4483): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AuthZen ( 4384): Starting Enrollment...
,I/GLSUser ( 1885): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1885): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/AuthZen ( 4384): getting auth token. Attempt 0
,I/GCoreUlr( 1780): DispatchingService.onDestroy()
,D/PMS     (  971): acquireWL(7e945a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1780 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): releaseWL(7e945a): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,I/GCoreUlr( 1780): Unbound from all location providers
,I/GLSUser ( 1885): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/GLSUser ( 1885): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1885): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1885): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1885): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AuthZen ( 4384): Error getting auth token
E/AuthZen ( 4384): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 4384): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4384): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4384): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4384): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZen ( 4384): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 4384): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 4384): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 4384): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 4384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 4384): 	at android.os.Looper.loop(Looper.java:155)
E/AuthZen ( 4384): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     (  971): Explicit concurrent mark sweep GC freed 16030(873KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 1.533ms total 127.986ms,
,D/a       ( 4384): Opening database auth.proximity.permit_store...,
,D/AuthZenTransactionCache( 4384): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4384): Clearing transaction cache,
,D/PMS     (  971): acquireWL(2cfffe14): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 971 1000 null
,D/PMS     (  971): releaseWL(2cfffe14): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/Babel_SMS( 4483): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 4483): MmsConfig.loadMmsSettings
D/MmsCustomizationProvider( 3829): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3829): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,I/Babel_SMS( 4483): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
I/Babel_SMS( 4483): MmsConfig.loadFromDatabase
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4483, uid=10112, userID:0
,E/Babel_SMS( 4483): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4483): MmsConfig.loadFromResources
,E/Babel_SMS( 4483): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 4483): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,W/Settings( 4483): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
I/Babel_Crash( 4483): startup - clean
,I/Babel   ( 4483): deleted: false for 0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4483, uid=10112, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0,
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4483, uid=10112, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4483, uid=10112, userID:0
,W/VideoCapabilities( 4483): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4483): Unsupported mime video/x-ms-wmv
,W/Utils   ( 4483): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 4483): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4483): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4483): Unsupported mime audio/qcelp
,W/VideoCapabilities( 4483): Unsupported mime video/x-ms-wmv,
,I/VideoCapabilities( 4483): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 4483): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 4483): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4483): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4483): Unrecognized profile 2130706433 for video/avc,
,I/vclib   ( 4483): onServiceConnected,
W/Babel   ( 4483): Attempted to change video mute state without an active call.
,I/ActivityManager(  971): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4517 uid=10176 gids={50176, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,W/ResourcesManager( 4517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 4517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 4517): Installed default security provider GmsCore_OpenSSL
,E/cutils-trace( 4550): Error opening trace file: Permission denied (13)
,I/dex2oat ( 4550): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads478730363.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads478730363.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 4550): dex2oat: override thread count:4
,I/dex2oat ( 4550): dex2oat took 35.138ms (threads: 4)
,W/art     ( 4517): Suspending all threads took: 10.720ms,
,E/YouTube MDX( 4517): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 4517): [NET] android_getaddrinfofornet+,hn 9(0x3132372e302e30),sn(),hints(known),family 0,flags 4,
D/libc    ( 4517): [NET] android_getaddrinfofornet-, SUCCESS
,D/VoldConnector(  971): SND -> {11 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache,
,D/VoldConnector(  971): SND -> {12 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/VoldConnector(  971): SND -> {13 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files,
,D/VoldConnector(  971): SND -> {14 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/files/
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4517): Found 10024
,D/VoldConnector(  971): SND -> {15 volume mkdirs /storage/ext_sd/Android/data/com.google.android.youtube/cache/},
I/ActivityManager(  971): Waited long enough for: ServiceRecord{24e069fb u0 com.htc.autobot/.htcmodeclient.HtcModeService}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.youtube/cache/
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4596 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  971): killProcessQuiet, pid=3946
I/ActivityManager(  971): Killing 3946:com.htc.feedback/u0a83 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/HtcModeClient( 3273): handler message = 4011,
,E/HtcModeClient( 3273): Check connection and retry 3 times.
,I/ActivityManager(  971): Recipient 3946
,V/AlarmManager(  971): sending alarm PendingIntent{34246828: PendingIntentRecord{22cb941 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=55472, Int=259200000
V/AlarmManager(  971): sending alarm PendingIntent{1cc72c27: PendingIntentRecord{3d6bded4 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457596459719, Int=0
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/iu.UploadsManager( 4384): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400,
,I/iu.UploadsManager( 4384): End new media; added: 0, uploading: 0, time: 52 ms,
,I/Gmail   ( 4596): getAccountsCursor
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GAV2    ( 4596): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4596, uid=10106, userID:0
W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 4596): Observing account changes for notifications,
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4596, uid=10106, userID:0
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4596, uid=10106, userID:0
,E/Gmail   ( 4596): Error finding the version of the Email provider.....
E/Gmail   ( 4596): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4596): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4596): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4596): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4596): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4596): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4596): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4596): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4596): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4596): getAccountsCursor,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4596, uid=10106, userID:0,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4596, uid=10106, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4596, uid=10106, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4596, uid=10106, userID:0
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  971): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4640 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4596, uid=10106, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4596, uid=10106, userID:0
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
E/ActivityThread( 4596): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2065918e that was originally bound here
E/ActivityThread( 4596): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2065918e that was originally bound here
E/ActivityThread( 4596): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4596): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4596): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4596): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4596): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4596): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4596): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4596): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4596): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4596): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4596): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4596): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4596): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4596): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4596): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4596): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  971): Unbind failed: could not find connection for android.os.BinderProxy@3f6ae80f
,E/SQLiteLog( 4596): (283) recovered 1541 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal,
,I/Gmail   ( 4596): notifyAccountChanged
,I/Gmail   ( 4596): calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,I/Gmail   ( 4596): getAccountsCursor,
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  971): acquireWL(ffdca07): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4596 10106 null
,I/Gmail   ( 4596): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/Gmail   ( 4596): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PMS     (  971): acquireWL(ffdca07): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4596 10106 null
,I/Gmail   ( 4596): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,D/PMS     (  971): acquireWL(ffdca07): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4596 10106 null
,I/Gmail   ( 4596): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4596, uid=10106, userID:0,
D/Process (  971): killProcessQuiet, pid=3968,
I/ActivityManager(  971): Killing 3968:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Gmail   ( 4596): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4596): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  971): Recipient 3968,
,I/Gmail   ( 4596): master sync=false, engine sync=true,
,D/LocationManagerService(  971): getProviders()=[passive]
,I/Gmail   ( 4596): getAccountsCursor,
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4596): master sync=false, engine sync=true,
,I/ActivityManager(  971): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4674 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4640, uid=10085, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4640, uid=10085, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4640, uid=10085, userID:0
,E/AndroidHttpClient( 4323): Leak found
E/AndroidHttpClient( 4323): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4323): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4323): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4323): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4323): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4323): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4323): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4323): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4323): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4323): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4323): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4323): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4323): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4323): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4323): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4323): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4323): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  971): Explicit concurrent mark sweep GC freed 11447(594KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/23MB, paused 1.365ms total 164.603ms
,D/WifiService(  971): New client listening to asynchronous messages
E/WifiTrafficPoller(  971): ADD_CLIENT: 6
W/BroadcastQueue(  971): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/VelvetNetworkClient( 4640): Network connection not availble
,I/ActivityManager(  971): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4712 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,D/Process (  971): killProcessQuiet, pid=3993
I/ActivityManager(  971): Killing 3993:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/WebViewFactory( 4640): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/ActivityManager(  971): Recipient 3993
,D/GCM     ( 1885): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1885): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4384): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/LibraryLoader( 4640): Time to load native libraries: 22 ms (timestamps 8356-8378)
,I/LibraryLoader( 4640): Expected native library version number "",actual native library version number ""
,W/art     ( 4640): Attempt to remove local handle scope entry from IRT, ignoring,
,I/ActivityManager(  971): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4740 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4384, uid=10024, userID:0
,W/ResourcesManager( 4740): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 93
W/ResourcesManager( 4740): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
D/AccFlag ( 1457): sku_id=118
,I/MultiDex( 4740): VM with version 2.1.0 has multidex support,
,I/ActivityManager(  971): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4767 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/MultiDex( 4740): install
I/MultiDex( 4740): VM has multidex support, MultiDex support library is disabled.
D/LocationInitializer( 4384): Restart initialization of location
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 91
,D/AccFlag ( 1457): sku_id=118
,V/JNIHelp ( 4740): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
,D/AccFlag ( 1457): sku_id=118
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 49
,D/AccFlag ( 1457): sku_id=118
W/art     ( 4640): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityThread( 4740): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 4740): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@191f7a3e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4740): Installed default security provider GmsCore_OpenSSL
D/Process (  971): killProcessQuiet, pid=4040
I/ActivityManager(  971): Killing 4040:com.google.android.configupdater/u0a98 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 4040
,I/ActivityManager(  971): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4798 uid=10076 gids={50076, 9997} abi=arm64-v8a
,I/ActivityManager(  971): Killing 4134:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=4134
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  425): Explicit concurrent mark sweep GC freed 8655(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 215us total 30.541ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 21.786ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 22.526ms
,I/ActivityManager(  971): Recipient 4134
,D/WearableService( 4740): callingUid 10024, callindPid: 4740
,D/SMSBackup( 4798): Got a database change event,
,I/ActivityManager(  971): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4820 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,I/ActivityManager(  971): Killing 4161:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=4161
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 4161
,E/MDM     ( 1780): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ImageRamCache( 4820): create image Cache, size: 31457280.,
,I/ImageRamCache( 4820): [resize] ImageRamCache resized to: 30Mb.,
I/ImageRamCache( 4820): create image Cache, size: 31457280.
,I/FeedSettings( 4820): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
,I/FeedSettings( 4820): GroupBudget 0.500000 0.380000
I/FeedSettings( 4820): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4820): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4820): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 4820): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 4820): [custom highlight] onReceive,
,D/CustomHighlightService( 4820): [custom highlight] onHandleIntent,
,D/NewsDB  ( 4820): set custom highlight []
,I/ActivityManager(  971): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4847 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC <<
,D/CustomHighlightService( 4820): [custom highlight] set tags 
,D/Process (  971): killProcessQuiet, pid=4230
I/ActivityManager(  971): Killing 4230:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  971): releaseWL(ffdca07): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,I/ActivityManager(  971): Recipient 4230,
,D/MessagingShortcutReceiver( 3829): keep hiding shortcut bubble,
,D/MessagingShortcut( 3829): updateMsgShortcut, msg count> -1
,D/MessagingShortcut( 3829): After query: 0
D/MessagingShortcut( 3829): mPresentUnreadCount: -1
,D/MessageUtils( 3829): [getShortcut] com.htc.sense.mms.ui.ConversationList, false,
D/MessagingShortcut( 3829): setMsgShortcutDrawable> 0, false
,D/MessagingShortcut( 3829): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2,
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] reorderNotification, total:0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  971): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4869 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,W/ResourcesManager( 4869): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,I/ActivityManager(  971): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4891 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/TodoTaskshortcut( 4869): update TASK shortcut>
,I/[PluginManager]RegisterService( 1421): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello,
I/[PluginManager]RegisterService( 1421): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1518): action: android.intent.action.PACKAGE_ADDED
,D/Process (  971): killProcessQuiet, pid=4251
I/ActivityManager(  971): Killing 4251:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MdScBoot( 4847): [18.1.] 30@-075354 -> 40,
,D/MdScBootUi( 4847): [18.1.2.] boot 118,
,D/MdScSimSt( 4847): [18.1.2.] qry 118: 0+1 running 0
,I/ActivityManager(  971): Recipient 4251,
,I/DeviceManagement( 4080): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  971): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4921 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a,
,D/HtcCupdReceiver(Provider)( 4921):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED,
,I/ActivityManager(  971): Killing 4276:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17,
D/Process (  971): killProcessQuiet, pid=4276
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/Settings:HtcWirelessFeatureFlags( 4208): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 4208): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4208): The wrap header doesn't exist in header list.,
,I/ActivityManager(  971): Recipient 4276,
,E/Settings:HtcWrapHeaderInfo( 4208): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 4208): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]support         :false
,I/ActivityManager(  971): Killing 4300:com.android.smith/1000 (adj 15): empty #17,
D/Process (  971): killProcessQuiet, pid=4300
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/ActivityManager(  971): Recipient 4300,
,D/Process (  971): killProcessQuiet, pid=4360
I/ActivityManager(  971): Killing 4360:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  971): Recipient 4360
,E/Settings:HtcVoWifiWidgetEnabler( 4208): isSupportVoWifi: null,
I/ActivityManager(  971): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4208): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4208): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4208): updateDevelopment, bPrefShow = true
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4384): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 4384): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello,
,D/PMS     (  971): acquireWL(111246a9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4384 10024 null
,E/Settings:HtcUmcWidgetEnabler( 4208): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4208): [supportHomeButton]support         :false
,I/ActivityManager(  971): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4208): isSupportVoWifi: null
E/ActivityThread( 4208): Failed to find provider info for com.htc.vowifi
,I/ConfigFetchService( 4384): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/PMS     (  971): acquireWL(f9fa465): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4384 10024 WorkSource{10374 com.example.hello},
I/ConfigFetchService( 4384): launchTask
,D/PMS     (  971): releaseWL(111246a9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  971): acquireWL(162df53a): PARTIAL_WAKE_LOCK  Icing 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4384): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.vision from APK com.google.android.gms,
,V/ConfigFetchTask( 4384): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WKcWMWvCU23ME-060oMI-0Nt2IjOb3iC_tLRYeRUCexn4OtPmmJcXEgqD3ZCQtJ-bFpFS_Ud9Gl0JMrv656wJP4FJRw9Yser-Q7_IOhdj7HzT8Olja7A3gGIHINz5t70wYo6olADobN6Ier3TB-mXNIhOx9wtE1MCFa8SbOLKn9wnkIVvfXavfqa9XQEjp-EPn0pB_
,D/Vision  ( 4384): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) },
,I/PeopleContactsSync( 4384): CP2 sync disabled
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4384, uid=10024, userID:0
D/Vision  ( 4384): Failed to find package metadata for com.example.hello
D/Vision  ( 4384): No vision deps
I/GoogleURLConnFactory( 4384): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  971): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4956 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/ActivityManager(  971): Waited long enough for: ServiceRecord{6df1938 u0 com.htc.HTCSpeaker/.NGFService}
,I/Icing   ( 4384): Storage manager: low false usage 2.04MB avail 5.80GB capacity 7.95GB,
,D/libc    ( 4384): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4384): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4384): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    ( 4384): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4384): [NET] android_getaddrinfo_proxy+
D/libc    ( 4384): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4384): [NET] android_getaddrinfo_proxy-, NODATA
,W/Icing   ( 4384): Received bad json for section weights override -- ignoring.
,W/ConfigFetchTask( 4384): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4384): fetch service done; releasing wakelock
,D/PMS     (  971): releaseWL(f9fa465): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10374 com.example.hello}
,I/ConfigFetchService( 4384): stopping self
,W/Icing   ( 4384): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 4384): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4384): Received bad json for corpus context scoring override -- ignoring.
,W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,E/Icing   ( 4384): Loading extension by file descriptor -1 failed
,I/art     ( 1885): Explicit concurrent mark sweep GC freed 10075(557KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 761us total 49.897ms,
,W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,W/BaseAppContext( 4384): Using Auth Proxy for data requests.
,I/Icing   ( 4384): updateResources: need to parse f{com.google.android.gms},
,I/Icing   ( 4384): Internal init done: storage state 0,
,I/Icing   ( 4384): Post-init done,
,D/PMS     (  971): releaseWL(162df53a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/GAv4    ( 4956): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4956):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4956):   adb logcat -s GAv4
,W/GAv4    ( 4956): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4956): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4956): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/AnalyticsTrackerProxyImpl( 4956): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45,
,I/HtcModeClient( 3273): handler message = 4011,
E/HtcModeClient( 3273): Check connection and retry 4 times.
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4384): Module APK com.google.android.play.games already loaded
,D/VoldConnector(  971): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,W/ContextImpl( 4956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5000 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  971): Killing 4517:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=4517
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,W/ResourcesManager( 4956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 4956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Recipient 4517
,V/AlarmManager(  971): sending alarm PendingIntent{1abc36bf: PendingIntentRecord{ce9cba6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=62044, Int=0
,W/ResourcesManager( 5000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,V/JNIHelp ( 4956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4956): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4956): Installed default security provider GmsCore_OpenSSL
,I/GAV2    ( 4596): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 4384): Google Analytics 7.8.99 is starting up.
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  971): acquireWL(39a4a624): PARTIAL_WAKE_LOCK  AsyncService 0x1 5000 10167 null,
,D/PMS     (  971): acquireWL(2f1de342): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5000 10167 null,
,D/PMS     (  971): releaseWL(39a4a624): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  971): releaseWL(2f1de342): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,D/PMS     (  971): acquireWL(35980090): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4869 10069 null,
,D/PMS     (  971): acquireWL(21444d89): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4869 10069 null
,D/PMS     (  971): releaseWL(35980090): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4869): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4869): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,W/System.err( 4869): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4869): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/PMS     (  971): releaseWL(21444d89): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 4869): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/UpdateIcingCorporaServi( 4640): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE,
,W/NotifyReceiver( 4869): stopSelfResult true
,D/MtpReceiver( 3771): [MTP][handleUsbStateAsync]+,
D/PMS     (  971): acquireWL(32364daf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1885 10024 WorkSource{10024 com.google.android.gms}
D/MtpReceiver( 3771): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3771): [MTP][handleUsbState]+
,I/ActivityManager(  971): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5039 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/MtpReceiver( 3771): [MTP][scanExternalVolumeIfNeed] scan external volume
,D/MtpReceiver( 3771): [MTP][handleUsbState]-
D/MtpReceiver( 3771): [MTP][handleMessage]-
,D/PMS     (  971): releaseWL(32364daf): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,W/asset   ( 4640): Copying FileAsset 0x559e87a5a0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/UpdateIcingCorporaServi( 4640): UpdateCorporaTask done [took 101 ms] updated apps [took 101 ms] 
,I/ActivityManager(  971): Killing 4596:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=4596
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  971): Explicit concurrent mark sweep GC freed 12797(640KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.255ms total 180.629ms,
,I/ActivityManager(  971): Recipient 4596
,D/SyncApplication( 5039): Loading default preferences
,D/MtpService( 3771): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 3771): TotalSize=1886532,MediaCacheLimit=6000
D/PMS     (  971): acquireWL(cbb24c1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4384 10024 null,
,D/MtpService( 3771): [isMtpConnected] connected: true
,W/Resources( 5039): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,I/iu.UploadsManager( 4384): End new media; added: 0, uploading: 0, time: 51 ms,
D/PMS     (  971): releaseWL(cbb24c1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,E/WifiTrafficPoller(  971): ADD_CLIENT: 7,
D/WifiService(  971): New client listening to asynchronous messages
,D/SyncApplication( 5039): Overriding preferences with custom values,
,D/SyncApplication( 5039): Updating preferences succeeded
,E/SyncApplication( 5039): Application created.
,W/VolumeInfo( 5039): Unable to read mount points,
W/VolumeInfo( 5039): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5039): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5039): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5039): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5039): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5039): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5039): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5039): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5039): 	,at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5039): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5039): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5039): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5039): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5039): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5039): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5039): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5039): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5039): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5039): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5039): ,	... 13 more
V/VolumeInfo( 5039): Found 0 mount point(s)
V/VolumeInfo( 5039): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
E/MediaScannerService( 3771): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3771): [handleMessage] --- Should not be here, ignore request. ----
,D/VolumeInfo( 5039): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/,
,I/CalendarDefines( 5039): getNewCalendarAuthority()...,
,D/VolumeInfo( 5039): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5039): Can not create volume ID for unmounted volume null
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5039, uid=10005, userID:0
,W/PackageManager(  971): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 5039): enableAppOperation()+
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5039, uid=10005, userID:0
W/PackageManager(  971): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 5039): enableAppOperation()-
,D/HTCUtilities( 5039): isNeorSinged() + 
,D/HTCUtilities( 5039): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5039): isNeorSinged() return false
,D/CDMountReceiver( 5039): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 5039): USB connected to PC
,D/FOTAReceiver( 5039): onReceive() enter ,
,D/FOTAReceiver( 5039): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/TetherSettings( 4208): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4208): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4208): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4208): Cust_ConnectToPC   : spcsc>false
D/        ( 4208): Cust_ConnectToPC   : IPT>true
D/        ( 4208): Cust_ConnectToPC   : Singel_USB>false,
W/Settings( 4208): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4208): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4208): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4208): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4208): usb_cable_connect = 1
,D/SmartNS_Utility( 4208): usb_denied = 0
,I/SmartNS_NSReceiver( 4208): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4208): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 4208): onReceive:com.htc.intent.action.USB_CONNECT2PC,
,W/ContextImpl( 4208): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  971): acquireWL(2234adc0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1885 10024 WorkSource{10024 com.google.android.gms},
I/SmartNS_PSService( 4208): onReceive:com.htc.intent.action.USB_CONNECT2PC
D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1885): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1885): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1885): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1885): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  971): releaseWL(2234adc0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1885): [NET] android_getaddrinfo_proxy-, NODATA
W/Settings( 4208): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4208):  defaultType:0
I/SmartNS_PSService( 4208): fail notificaiton:false
,D/SmartNS_Utility( 4208): usb_cable_connect = 1
E/MediaScannerServiceEx( 3771): [getStorageMaskIdFromPath] path is null
D/SmartNS_Utility( 4208): usb_denied = 0
I/SmartNS_PSService( 4208): usb notificaiton:true
D/MediaScannerServiceEx( 3771): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/MediaScannerServiceEx( 3771): [handleExternalVolume] ext storage
D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3771): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 3771): [update][9]#0#
,I/ActivityManager(  971): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/MediaProvider( 3771): [update][2]#0#
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted,
D/MtpService( 3771): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/SmartNS_Utility( 4208): usb_cable_connect = 1
D/MediaProvider( 3771): [update][18]#1#
D/SmartNS_Utility( 4208): usb_denied = 0
,I/SmartNS_PSService( 4208): usb notificaiton:true
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/MediaScannerServiceEx( 3771): [AliveExtStorageRows]-0, 0
,D/PMS     (  971): acquireWL(3fdeaaf9): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3771 10017 null
,D/MediaScanner( 3771): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
,D/SmartNS_Utility( 4208): usb_cable_connect = 1,
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36
,D/SmartNS_Utility( 4208): usb_denied = 0
,I/SmartNS_PSService( 4208): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4208): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  971): Killing 4767:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
,D/Process (  971): killProcessQuiet, pid=4767
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 4767,
,W/ContextImpl( 5073): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
D/Process (  971): killProcessQuiet, pid=4798
,I/ActivityManager(  971): Killing 4798:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/SocialFeedProvider( 1518): +disConnect socialManager,
I/SocialFeedProvider( 1518): disconnect socialManager
,I/ActivityManager(  971): Recipient 4798,
,I/SocialFeedProvider( 1518): -disConnect socialManager,
V/AlarmManager(  971): sending alarm PendingIntent{1096e5ec: PendingIntentRecord{ad5fdb5 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457596466670, Int=0
,I/ActivityManager(  971): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5096 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/SocialManager[SocialBiLogHelper]( 4820): action: com.htc.sense.hsp.HANDLE_ULOG,
I/SocialManager[SocialBiLogHelper]( 4820): last commit ulog time 1457533327260
I/SocialManager[SocialBiLogHelper]( 4820): skip commit this time
,I/ActivityManager(  971): Killing 4847:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
,D/Process (  971): killProcessQuiet, pid=4847
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 4847,
,D/MediaProvider( 3771): [update][15]#1#,
,D/MediaScanner( 3771):  prescan time: 348ms,
D/MediaScanner( 3771):     scan time: 548ms
,D/MediaScanner( 3771): postscan time: 3ms
D/MediaScanner( 3771):    total time: 899ms
D/MediaScanner( 3771): -----------------------------------------------------------------
D/MediaScanner( 3771): firstscan(media) time: 274ms
D/MediaScanner( 3771): secondscan(non-media) time: 274ms
D/MediaScanner( 3771):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
,D/MediaScanner( 3771):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3771):  [Total]    File(Image+Video+Audio+Others) in database : 1549
,D/MediaProvider( 3771): [delete][7]
,D/MediaProvider( 3771): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3771): [recoverParentNodes] - 0,
D/MediaProvider( 3771): [update][7]
,D/MediaScannerServiceEx( 3771): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3771): [updateImage]+
,W/ResourcesManager( 5096): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/MediaScannerServiceEx( 3771): [updateImage]-0
,D/PMS     (  971): releaseWL(3fdeaaf9): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null,
D/MediaScannerServiceEx( 3771): [1] scan finished
,D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3771): Process mounted intent for unmounted storage: /storage/ext_sd,
D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]+131073
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted,
,D/MediaProvider( 3771): [update][15]#1#
,D/MediaProvider( 3771): [update][26]#0#,
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]--1, 0
,D/MediaProviderUtils( 3771): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3771): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3771): calcVolumeId: /storage/usb
,D/MediaScannerServiceEx( 3771): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3771): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]+196609,
,D/MediaProvider( 3771): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,I/CalendarProvider2( 5096): Created com.android.providers.calendar.CalendarAlarmManager@29ba95c4(com.htc.providers.calendar.HtcCalendarProvider@37abacad)
D/MediaProvider( 3771): [update][13]#1#
,D/CalendarProvider2( 5096): wait start:true,
,D/MediaProvider( 3771): [update][30]#0#,
,D/MediaScannerServiceEx( 3771): [disAliveExtStorageRows]--1, 0,
,D/FlexNetS( 5096): updateSvcAllowedInSettings:false,
,D/CalendarProvider2( 5096): wait end:false
,I/ActivityManager(  971): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5123 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=3829
,I/ActivityManager(  971): Killing 3829:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 3829
,W/ContextImpl( 5123): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 5123): MY_DEBUG = false
,D/PMS     (  971): acquireWL(f434469): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5123 1000 null,
,I/ActivityManager(  971): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5148 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,D/PowerUsageService( 5123): repeat time = 1457597367441
,D/WeatherUtility( 1421): Weather sync is On,
,D/WSP     ( 1421): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/art     (  425): Explicit concurrent mark sweep GC freed 8667(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 318us total 34.142ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 232us total 28.522ms
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4384, uid=10024, userID:0
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 181us total 26.758ms
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4384, uid=10024, userID:0
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4384, uid=10024, userID:0
,I/ActivityManager(  971): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5173 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,D/WeatherUtility( 5148): Weather sync is On
,W/ResourcesManager( 5173): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5194 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/PowerUsageList:PowerUsageHelper( 5123): PowerProfile::POWER_SCREEN_FULL = 154.8
,W/WeatherRequest( 5148): request cur loc, but there is no sys cur,
W/Settings( 5148): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 5148): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/PowerUsageList:BatterySipperExt( 5123): gen(), null == sipper.uidObj, userId = 0,
,I/RemoteViews( 1518): reapply : com.htc.widget.weatherclock 9 17
,W/SystemReader(  971): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1685): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1685): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PhoneApp( 1457): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,W/Prism.AllAppsManager( 1518): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/ResourcesManager(  971): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Prism.ItemManager( 4820): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4820): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1518): Deferring update until onResume
D/Launcher( 1518): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1685): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,E/ExternalAccountType( 1685): Unsupported attribute readOnly,
,W/PackageManager(  971): Unable to load service info ResolveInfo{24472b49 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  971): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  971): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  971): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  971): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  971): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  971): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  971): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  971): 	at com.android.server.SystemServer.main(SystemServer.java:225)
,W/PackageManager(  971): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  971): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  971): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/EASAppSvc( 5194): [ NA ]onCreate,
,I/VersionUtil( 5194): [ NA ]setIsFOTAing: true,
,I/VersionUtil( 5194): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5194): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 5194): Set CursorWindow size to: 4194304 KB, Tid: 5219
,D/ORMLib  ( 4869): put(),
,D/PowerUsageService( 5123): calcPower(), no data
,V/GmsNetworkLocationProvi( 1780): DISABLE,
I/GCoreNlp( 1780): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5226 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=4891
I/ActivityManager(  971): Killing 4891:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 4891
,D/LocationProviderProxy(  971): applying state to connected service
,D/PMS     (  971): acquireWL(192265a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,I/EASAppSvc( 5194): [ NA ]onDestroy
,D/PMS     (  971): releaseWL(192265a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
E/SQLiteLog( 5173): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,D/LocationProviderProxy(  971): applying state to connected service
,I/CalendarProvider2( 5096): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 5096): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/EASAppSvc( 5194): [ NA ]onCreate
,I/VersionUtil( 5194): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5194): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5194): [ NA ]setIsFOTAing: false
,D/PMS     (  971): acquireWL(d6c3f1b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,D/Process (  971): killProcessQuiet, pid=4483
I/ActivityManager(  971): Killing 4483:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/WifiService(  971): New client listening to asynchronous messages,
E/WifiTrafficPoller(  971): ADD_CLIENT: 8
,W/EAS_NetworkUtil( 5194): [ NA ]getNetworkInfo: NetworkInfo is null
,W/EAS_NetworkUtil( 5194): [ NA ]getNetworkInfo: NetworkInfo is null
I/EASAppSvc( 5194): [ NA ]> uninitEASService
D/PMS     (  971): releaseWL(d6c3f1b): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/ORMLib  ( 4869): put(),
,I/ActivityManager(  971): Recipient 4483
,I/EASRequestController( 5194): [ NA ]release
D/PMS     (  971): acquireWL(1c3348b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(1c3348b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/EASPublicBinder( 5194): [ NA ]release
D/TaskBinder( 5194): [ NA ]release
D/TaskBinder( 5194): [ NA ]release
I/EASAppSvc( 5194): [ NA ]< uninitEASService
,I/art     (  971): Explicit concurrent mark sweep GC freed 21154(1116KB) AllocSpace objects, 2(352KB) LOS objects, 33% free, 16MB/24MB, paused 1.517ms total 164.102ms
,I/EASAppSvc( 5194): [ NA ]onDestroy,
I/EASAppSvc( 5194): [ NA ]> uninitEASService
W/System.err( 5194): java.lang.IllegalArgumentException: Receiver not registered: null
,W/System.err( 5194): 	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:828)
W/System.err( 5194): 	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1798)
W/System.err( 5194): ,	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:510)
W/System.err( 5194): 	at com.htc.android.mail.eassvc.EASAppSvc.F(EASAppSvc.java:2451)
W/System.err( 5194): 	at com.htc.android.mail.eassvc.EASAppSvc.g(EASAppSvc.java:133)
W/System.err( 5194): 	at com.htc.android.mail.eassvc.i.run(EASAppSvc.java:1499)
,I/MusicStore( 5226): Database version: 120
,I/ActivityManager(  971): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5265 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a,
V/AlarmManager(  971): sending alarm PendingIntent{285b1f7: PendingIntentRecord{2b303864 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1457596468485, Int=0
,I/ActivityManager(  971): Killing 4674:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,D/Process (  971): killProcessQuiet, pid=4674
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ORMLib  ( 4869): put()
,D/PMS     (  971): acquireWL(91ff1ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(91ff1ce): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  971): Recipient 4674,
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): updateBatteryInfo,
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/NotificationService(  971): plugged=true pluggin=true
,D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PMS     (  971): runPSCheck
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: ApStaDisabledState
I/ActivityManager(  971): Killing 4080:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/WifiController(  971): processMsg: DefaultState
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  971): handleMessage: X
I/HtcPowerSaver(  971): << updateStatus
D/Process (  971): killProcessQuiet, pid=4080
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,I/ActivityManager(  971): Recipient 4080,
,I/ConfigService( 1885): onDestroy
,D/VoldConnector(  971): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5226): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/ActivityManager(  971): Killing 4921:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17,
D/Process (  971): killProcessQuiet, pid=4921
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/VoldConnector(  971): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5226): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  971): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5226): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/ActivityManager(  971): Recipient 4921,
,I/Prism.ItemManager( 1518): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1518): loadItems() com.htc.launcher.pageview.WidgetManager@365f55e7 +
I/Prism.WidgetManager( 1518): onLoadItems() +
,I/Prism.ItemManager( 4820): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4820): loadItems() com.htc.launcher.pageview.WidgetManager@106041e1 +
,I/Prism.WidgetManager( 4820): onLoadItems() +
,W/ResourcesManager( 5226): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5226): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1518): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4820): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 5226): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5226): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5226): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36df38: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5226): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5226): GMSCore installation verified
,I/ConfigStore( 5226): Config Database version: 1,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5226, uid=10159, userID:0
,D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
,D/MediaRouterService(  971): Client com.google.android.music (pid 5226): Registered
,D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
,I/MediaRouter( 5226): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,W/ResourcesManager( 1518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TelephonyReceiver( 1457): bind: true
,W/ResourcesManager( 4820): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5296 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  971): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5311 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5226, uid=10159, userID:0
,I/GHttpClientFactory( 5226): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/GoogleURLConnFactory( 5226): Using platform SSLCertificateSocketFactory
,I/DFPI.ApkInstallService( 5296): onHandleIntent
I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
,I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
,W/HtcWrapAdjustableCursorFactory( 5311): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/MessageFrequencyProvider( 5311): onCreate,
,I/ActivityManager(  971): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5346 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/GetPrviateResource( 5311): GetPrviateResource
,V/GetPrviateResource( 5311): GetPrviateResource
,D/GenericMessagesProvider( 5311): query uri: content://htc-messages/wappush/count,
E/SQLiteLog( 5311): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5311): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
,E/SQLiteConnection( 5311): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5311): DB info: errno = 2, errno message = No such file or directory
,D/MessageCustFlag( 5311): sense_version=6.0
,E/SQLiteDatabase( 5311): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.,
E/SQLiteDatabase( 5311): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5311): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5311): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5311): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5311): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5311): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5311): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 5311): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5311): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5311): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
I/HtcModeClient( 3273): handler message = 4011
W/System.err( 5311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5311): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5311): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/HtcModeClient( 3273): Check connection and retry 5 times.
W/System.err( 5311): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5311): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
,W/System.err( 5311): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5311): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5311): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5311): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 5311): 	at android.os.Binder.execTransact(Binder.java:454)
D/BTAccessoryUtil( 5311): createReceiver
D/BTAccessoryUtil( 5311): registerReceiver return intent = null
,D/MessageCustFlag( 5311): sku_id=118
,I/ActivityManager(  971): Killing 4323:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=4323
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/HtcBuildUtils( 5311): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5311): Cannot find qct_8960_interface, use default value instead
,D/PhoneApp( 1457): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1457): -- N1 =0
D/PhoneApp( 1457): -- N2 =0,
,D/PhoneApp( 1457): -- N3 =0
,W/asset   ( 1518): Copying FileAsset 0x559ec810a0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 4820): Copying FileAsset 0x559e97e010 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/ActivityManager(  971): Recipient 4323,
,E/Prism.WidgetManager( 1518): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1518): onLoadItems() -
I/Prism.ItemManager( 1518): loadItems() com.htc.launcher.pageview.WidgetManager@365f55e7 -
,D/PMS     (  971): releaseWL(f434469): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,I/Prism.WidgetManager( 4820): onLoadItems() -,
I/Prism.ItemManager( 4820): loadItems() com.htc.launcher.pageview.WidgetManager@106041e1 -
,D/TelephonyReceiver( 1457): switchBindHtcMsgCursor: null
,I/ActivityManager(  971): Killing 4956:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  971): killProcessQuiet, pid=4956
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 4956,
,I/ActivityManager(  971): Waited long enough for: ServiceRecord{1d4cd0e2 u0 com.htc.backup/.notifications.contextual.ContextualReminderControlService},
,I/ActivityManager(  971): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5371 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a
,D/VoldConnector(  971): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
W/ContextImpl( 5346): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache,
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService,
,D/PMS     (  971): acquireWL(22064489): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 5096 10011 null,
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
,V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm),
,E/SQLiteLog( 5096): (284) automatic index on view_events(_id)
,D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2,
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/DFPI.ApkInstallService( 5296): onHandleIntent
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
D/DFPI.ApkInstallService( 5296): check CID = HTC__102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence],
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
,D/PMS     (  971): releaseWL(22064489): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/DFPI.ApkInstallService( 5296): onHandleIntent
,I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
,I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96,
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/DFPI.ApkInstallService( 5296): onHandleIntent
I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  971): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5403 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30,
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac,
,D/TelephonyReceiver( 1457): bind: false
D/TelephonyReceiver( 1457): switchBindHtcMsgCursor: null
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30,
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9,
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5296): onHandleIntent
,I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5296): onHandleIntent,
I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
,I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/DFPI.ApkInstallService( 5296): onHandleIntent,
I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5296): check CID = HTC__102
,I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/GCM     ( 1885): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1885): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm),
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma),
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
V/GmsCoreStatsServiceLauncher( 4384): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4384, uid=10024, userID:0
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/WearableService( 4740): callingUid 10024, callindPid: 4740
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/LocationInitializer( 4384): Restart initialization of location
E/MDM     ( 1780): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/AuthorizationBluetoothService( 1885): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1885): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
V/GmsCoreStatsServiceLauncher( 4384): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4384, uid=10024, userID:0
,E/MDM     ( 1780): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/LocationInitializer( 4384): Restart initialization of location
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
,W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/art     (  971): Explicit concurrent mark sweep GC freed 25373(1230KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.441ms total 155.387ms
I/art     (  971): WaitForGcToComplete blocked for 79.010ms for cause HeapTrim
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActionCombine( 5403): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145),
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/RemoteViews( 1222): apply : com.htc.updater 1 11 1 36
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
D/PMS     (  971): acquireWL(28f206bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1885 10024 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/PMS     (  971): releaseWL(28f206bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) },
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
D/PMS     (  971): acquireWL(1cbc07d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1885 10024 WorkSource{10024 com.google.android.gms}
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,D/PMS     (  971): releaseWL(1cbc07d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/FindExtension( 1222): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/ThreadedRenderer( 1222): Defer allocateBuffers to drawing time
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/art     ( 4384): Background sticky concurrent mark sweep GC freed 14713(1132KB) AllocSpace objects, 15(300KB) LOS objects, 16% free, 6MB/8MB, paused 5.455ms total 48.658ms
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2),
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96,
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5445 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac,
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/art     ( 3771): Background sticky concurrent mark sweep GC freed 22(1024B) AllocSpace objects, 0(0B) LOS objects, 2% free, 4MB/4MB, paused 6.522ms total 10.466ms
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/PhoneMonitor( 5445): Register our PhoneStateListener
,D/Process (  971): killProcessQuiet, pid=5000
I/ActivityManager(  971): Killing 5000:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 ,
,D/PhoneMonitor( 5445): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 5445): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  971): Recipient 5000
,D/GCM     ( 1885): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
,D/ChimeraCfgMgr( 4384): Loading module com.google.android.gms.kids from APK com.google.android.gms,
I/Kids    ( 4384): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/Process (  971): killProcessQuiet, pid=4640
I/ActivityManager(  971): Killing 4640:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  971): acquireWL(6b1c6fa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1885 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  971): Recipient 4640
D/WifiService(  971): Client connection lost with reason: 4
,D/PMS     (  971): releaseWL(6b1c6fa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5469 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,D/Messaging( 5311): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 5311): networkCode: 
D/MessageCustFlag( 5311): sku_id=118
,D/MmsConfig( 5311): SIE smsPri: null
D/MmsConfig( 5311): networkCode: 
,D/MmsConfig( 5311): packageName: com.htc.vvm.att does not exist
,D/Messaging( 5311): mNeedToUpdateDate2 start
D/ReportIndicatorCache( 5311): startAsyncQueryReports ---
,D/MmsAsyncWorkHandler( 5311): 
D/MmsAsyncWorkHandler( 5311): HM tk = 20001
D/ReportIndicatorCache( 5311): MSG_QUERY_REPORTS >>
D/SettingsManager( 5311): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@3d836be2
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1457):  slotId = -1000
,D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 5311): [DraftCache/1] DraftCache.constructor,
D/DraftCache( 5311): [DraftCache/1] refresh
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1457): sku_id=118
,D/MmsConfig( 5311): networkCode: 
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/DraftCache( 5311): [DraftCache/122] rebuildCache
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 5311): ViewCache CreatePreloadOnlyConversationList
I/Messaging( 5311): mccmnc> 
,D/Messaging( 5311): mNeedToUpdateDate2: false
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1457):  slotId = -1000
D/MmsSmsV2Provider( 1457): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 5311): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
D/Jerry   ( 1457): URI_DRAFT,
,D/PhoneStorageUtil( 5311): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 5311): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 5311): createReceiver
,D/DraftCache( 5311): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 5311): [DraftCache/122] rebuildCache time: 15
D/MmsAsyncWorkHandler( 5311): 
D/MmsAsyncWorkHandler( 5311): HM tk = 20002
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/AccFlag ( 1457): sku_id=118
D/MessageCustFlag( 5311): sense_version=6.0
D/Jerry   ( 5311): start to preload cursor >>>>>>>
,D/TelephUtils( 1457): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 91
,V/MmsProvider( 1457): Update uri=content://mms, match=0
V/MmsProvider( 1457): selection=st=129 AND m_type!=134
,D/Messaging( 5311): Reset downloading state: 0
V/MmsSystemEventReceiver( 5311): TransactionService is going to be woken up.
D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/MmsSmsV2Provider( 1457):  slotId = -1000
,V/TransactionService( 5311): 1-Creating TransactionService
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/AccFlag ( 1457): sku_id=118
V/TransactionService( 5311): onStartCommand: 1
D/MmsSystemEventReceiver( 5311): unRegisterForConnectionStateChanges
,V/TransactionService( 5311): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 5311): Loading previous transactions.
,D/Messaging( 5311): ViewCache CreatePreload,
D/Messaging( 5311): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1457): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 91,
D/AccFlag ( 1457): device_type: 1
,D/TransactionService( 5311): Force clearing mTransactionList
,D/TransactionService( 5311): Force set service start id to 1
V/TransactionService( 5311): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 5311): unRegisterForConnectionStateChanges
,V/TransactionService( 5311): Destroying TransactionService,
D/TransactionService( 5311): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 5311): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler },
,D/Cust_MMSMS( 5311): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 5311): def_index: 0
,D/MsgPreferenceUtils( 5311): globalIndex = 1
,D/MsgPreferenceUtils( 5311): phone state: true,
D/MsgPreferenceUtils( 5311): sd state: false
D/MsgPreferenceUtils( 5311): vIndex = 0
,I/Babel_SMS( 5469): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 5469): MmsConfig.loadMmsSettings,
,D/MmsCustomizationProvider( 5311): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 5311): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 5469): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 5469): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5469): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5469): MmsConfig.loadFromResources
,E/Babel_SMS( 5469): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5469): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5469, uid=10112, userID:0
,W/Settings( 5469): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5469): startup - clean,
,I/Babel   ( 5469): deleted: false for 0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=5469, uid=10112, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=5469, uid=10112, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=5469, uid=10112, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5469, uid=10112, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5469, uid=10112, userID:0,
,D/PMS     (  971): acquireWL(e75ba03): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5469 10112 null,
,I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5526 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5469): Unsupported mime video/x-ms-wmv
,W/Utils   ( 5469): could not parse size range '64x64-1920X1080'
,W/AudioCapabilities( 5469): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5469): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5469): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5469): Unsupported mime video/x-ms-wmv
,I/VideoCapabilities( 5469): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/art     (  971): Explicit concurrent mark sweep GC freed 7110(373KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.282ms total 129.407ms,
I/vclib   ( 5469): onServiceConnected
,W/Babel   ( 5469): Attempted to change video mute state without an active call.,
,W/ResourcesManager( 5469): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5469): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 5526): getAccountsCursor,
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GAV2    ( 5526): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=5526, uid=10106, userID:0
,W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=5526, uid=10106, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=5526, uid=10106, userID:0
,I/Gmail   ( 5526): Observing account changes for notifications
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5526): Error finding the version of the Email provider.....,
E/Gmail   ( 5526): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5526): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5526): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5526): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5526): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 5526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5526): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5526): getAccountsCursor
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/GCM     ( 1885): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1885): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4384): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4384, uid=10024, userID:0
,E/MDM     ( 1780): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4384): Restart initialization of location
,E/SQLiteLog( 5526): (283) recovered 1542 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/PMS     (  971): acquireWL(2a550bc8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1885 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1885): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1885): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1885): [NET] android_getaddrinfo_proxy+
D/libc    ( 1885): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1885): [NET] android_getaddrinfo_proxy-, NODATA,
,D/PMS     (  971): releaseWL(2a550bc8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/art     ( 5469): Suspending all threads took: 6.553ms
,V/JNIHelp ( 5469): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Gmail   ( 5526): notifyAccountChanged,
,I/Gmail   ( 5526): calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,I/Gmail   ( 5526): getAccountsCursor,
I/Gmail   ( 5526): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Gmail   ( 5526): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5526): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/System  ( 5469): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5469): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1885): Explicit concurrent mark sweep GC freed 10771(520KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 804us total 60.998ms
,D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5296): onHandleIntent
,I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
,I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,E/PhoneInterfaceManager( 1457): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService,
I/Babel   ( 5469): connection state changed from UNKNOWN to DISCONNECTED,
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
,W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,W/VideoCapabilities( 5469): Unrecognized profile 2130706433 for video/avc
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  971): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 5296): onHandleIntent
,I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
,I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
I/Gmail   ( 5526): master sync=false, engine sync=true
,I/ActivityManager(  971): Resuming delayed broadcast
,I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/Gmail   ( 5526): getAccountsCursor
,D/PMS     (  971): releaseWL(e75ba03): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
D/DFPI.PIReciver( 5296): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/Gmail   ( 5526): master sync=false, engine sync=true
,I/DFPI.ApkInstallService( 5296): onHandleIntent
I/DFPI.ApkInstallService( 5296): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5296): check CID = HTC__102
I/DFPI.ApkInstallService( 5296): There is no Demo.apk in sd card or phone storage
,I/NotifUtils( 5526): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/art     ( 3771): Background sticky concurrent mark sweep GC freed 20(928B) AllocSpace objects, 0(0B) LOS objects, 0% free, 4MB/4MB, paused 5.690ms total 11.804ms
I/SoundPicker( 5371): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5371): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,D/PMS     (  971): acquireWL(11ece11a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5469 10112 null
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/ActivityManager(  971): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5600 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
D/PMS     (  971): releaseWL(11ece11a): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/NotifUtils( 5526): validateNotifications - cancelling 1729800001 for 61035162 / -317575340
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0,
,I/art     ( 5371): Explicit concurrent mark sweep GC freed 12739(813KB) AllocSpace objects, 2(40KB) LOS objects, 87% free, 303KB/2MB, paused 322us total 36.648ms
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/MediaStoreImporter( 5226): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5371): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5371): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5371): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/art     (  971): Explicit concurrent mark sweep GC freed 9244(466KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.150ms total 122.428ms,
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/LocationManagerService(  971): getProviders()=[passive],
I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5371): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/ActivityManager(  971): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5627 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5371): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/Process (  971): killProcessQuiet, pid=5039
I/ActivityManager(  971): Killing 5039:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  971): Recipient 5039
,D/WifiService(  971): Client connection lost with reason: 4
,D/Process (  971): killProcessQuiet, pid=4208
I/ActivityManager(  971): Killing 4208:com.android.settings/1000 (adj 15): empty #17
,I/SoundPicker( 5371): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,I/ActivityManager(  971): Recipient 4208,
,I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5371): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/[PluginManager]RegisterService( 1421): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1421): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5649 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
D/Process (  971): killProcessQuiet, pid=5073
I/ActivityManager(  971): Killing 5073:com.htc.backupreset/1000 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5073,
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5649): -onCreate()
,V/AlarmManager(  971): sending alarm PendingIntent{2a66babe: PendingIntentRecord{797971f com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457596474012, Int=0
,V/Settings:HtcSettingsApplication( 5649): [5649/5649] onCreate(),
,I/ActivityManager(  971): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5674 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  971): killProcessQuiet, pid=4820,
I/ActivityManager(  971): Killing 4820:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  425): Explicit concurrent mark sweep GC freed 8643(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 207us total 26.495ms
,D/Settings:HtcWirelessFeatureFlags( 5649): id/is att sku: 118/false
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 190us total 22.676ms
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 184us total 23.162ms
,E/Settings:HtcWrapHeaderInfo( 5649): no such activity!,
,I/ActivityManager(  971): Recipient 4820
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5649): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 5649): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5649): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasBackKey      :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]support         :false
,I/ActivityManager(  971): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 5649): Failed to find provider info for com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 5649): isSupportVoWifi: null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5649): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5649): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5649): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasRecentAppKey :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5649): [supportHomeButton]support         :false
,I/ActivityManager(  971): Cannot resolve ContentProvider=com.htc.vowifi,
,E/ActivityThread( 5649): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5649): isSupportVoWifi: null
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5674, uid=10072, userID:0
,W/global  ( 5674): [apache-http] Connection GC has been deprecated!
,D/Finsky  ( 5674): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5674): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5674): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5674): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  971): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5715 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/Settings( 5674): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 5674): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 5715): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5715): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5674, uid=10072, userID:0
,I/MultiDex( 5715): VM with version 2.1.0 has multidex support,
I/MultiDex( 5715): install
I/MultiDex( 5715): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 5674): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 5674): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 5674): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,V/JNIHelp ( 5715): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 5674): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 4384): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5743 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,D/Process (  971): killProcessQuiet, pid=5123
I/ActivityManager(  971): Killing 5123:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/PackageBroadcastService( 4384): Null package name or gms related package.  Ignoreing.
,W/ActivityThread( 5715): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5715): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@191f7a3e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5715): Installed default security provider GmsCore_OpenSSL
,I/HtcModeClient( 3273): handler message = 4011,
E/HtcModeClient( 3273): Check connection and retry 6 times.,
,I/ActivityManager(  971): Recipient 5123,
,D/PMS     (  971): acquireWL(34154f6e): PARTIAL_WAKE_LOCK  Icing 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
,I/Icing   ( 4384): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/PMS     (  971): releaseWL(34154f6e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(1803de46): PARTIAL_WAKE_LOCK  AsyncService 0x1 5743 10167 null,
,D/Process (  971): killProcessQuiet, pid=5148,
I/ActivityManager(  971): Killing 5148:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  971): releaseWL(1803de46): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,I/ActivityManager(  971): Recipient 5148
,D/PMS     (  971): acquireWL(35745d34): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5743 10167 null,
,I/UpdateIcingCorporaServi( 5600): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
V/Finsky  ( 5674): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ActivityManager(  971): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5781 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,D/PMS     (  971): releaseWL(35745d34): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null,
,W/ResourcesManager( 5781): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 5781): onCreate
,D/Finsky  ( 5674): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  971): sending alarm PendingIntent{29203da3: PendingIntentRecord{249418a0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457596475404, Int=0
,D/ProviderChangeReceiver( 5781): ---------------------------------------------------
,D/ProviderChangeReceiver( 5781): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/HtcAlertService( 5781): start to updateAlertNotification!
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WSP     ( 1421): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1421): Weather sync is On
,I/WSP     ( 1421): [Receiver] next auto-sync alarm event is 60 mins later, at time: Thu Mar 10 09:54:35 CET 2016
,W/WSP     ( 1421): [Receiver] can't get active network info
,D/HtcAlertService( 5781): No fired or scheduled alerts,
D/HtcAlertUtils( 5781): -- cancelReminderNotification --
D/HtcAlertUtils( 5781): broadcastExistReminder!
I/UpdateIcingCorporaServi( 5600): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/GLSUser ( 1885): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1885): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1885): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1885): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/WSP     ( 1421): [SyncService] no data connection, stop sync service
I/Task_Calendar( 4869): Set ICALENDAR_UID to sync_data7 due to SDK_INT is 21
,I/ActivityManager(  971): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5812 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TodoTaskshortcut( 4869): update TASK shortcut>
,W/Finsky  ( 5674): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncApplication( 5812): Loading default preferences,
I/GLSUser ( 1885): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1885): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1885): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1885): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Resources( 5812): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiTrafficPoller(  971): ADD_CLIENT: 7
D/WifiService(  971): New client listening to asynchronous messages
,I/GLSUser ( 1885): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1885): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1885): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1885): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncApplication( 5812): Overriding preferences with custom values,
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncApplication( 5812): Updating preferences succeeded
W/Finsky  ( 5674): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/SyncApplication( 5812): Application created.
,W/VolumeInfo( 5812): Unable to read mount points
W/VolumeInfo( 5812): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5812): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5812): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5812): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5812): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5812): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5812): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5812): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5812): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5812): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5812): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5812): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5812): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5812): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5812): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5812): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5812): 	at libcore.io.Posix.open(Native Method),
W/VolumeInfo( 5812): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5812): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5812): 	... 13 more
V/VolumeInfo( 5812): Found 0 mount point(s)
V/VolumeInfo( 5812): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 5812): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 5812): getNewCalendarAuthority()...
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5812, uid=10005, userID:0
,W/PackageManager(  971): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5812, uid=10005, userID:0
W/PackageManager(  971): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 5812): enableAppOperation()+,
,D/SyncApplication( 5812): enableAppOperation()-,
,D/VolumeInfo( 5812): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,W/VolumeInfo( 5812): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 5812): isNeorSinged() + 
,D/HTCUtilities( 5812): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 5812): isNeorSinged() return false
,D/CDMountReceiver( 5812): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 5812): showNotification() contentText=If HTC Sync Manager setup doesn't start automatically on your computer, download it from www.htc.com/hsm
,I/ActionCombine( 5812): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,E/AndroidHttpClient( 5674): Leak found
E/AndroidHttpClient( 5674): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5674): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5674): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5674): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5674): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5674): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5674): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5674): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5674): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5674): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5674): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5674): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5674): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5674): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824),
D/CDMountReceiver( 5812): enable CD Auto-mount: true
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
D/PMS     (  971): releaseWL(23eed6e8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10005}
,D/HTCUtilities( 5812): enable auto-mount
D/HTCUtilities( 5812): enable auto-mount
,D/PMS     (  971): acquireWL(3a087bc4): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 5226 10159 null
,I/HtcMountManagerAdapter( 5812): mHtcMountManager is  null
I/HtcMountManagerAdapter( 5812): mHtcMountManager is  null
,I/HtcMountManagerAdapter( 5812): mStorageManager is  not null
I/HtcMountManagerAdapter( 5812): mStorageManager is  not null
,D/VoldConnector(  971): SND -> {22 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
D/VoldConnector(  971): SND -> {21 mountISO mount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,D/MountService(  971): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  971): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1222): apply : com.nero.android.htc.sync 0 14 8 38,
,I/RemoteViews( 1222): apply : com.nero.android.htc.sync 0 12 4 53,
,I/art     (  971): Explicit concurrent mark sweep GC freed 12883(596KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.436ms total 175.148ms
,D/PMS     (  971): acquireWL(3a717265): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10024}
V/AlarmManager(  971): sending alarm PendingIntent{248d3548: PendingIntentRecord{140bcfe1 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457596475825, Int=0
,D/PMS     (  971): releaseWL(3a717265): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=5226, uid=10159, userID:0,
D/PMS     (  971): releaseWL(3a087bc4): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 5226): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 5226): Stop autocaching.
,D/GCM     ( 1885): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1885): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4384): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/iu.UploadsManager( 4384): End new media; added: 0, uploading: 0, time: 83 ms,
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1780): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4384, uid=10024, userID:0,
,D/LocationInitializer( 4384): Restart initialization of location,
,E/GmsUtils( 5226): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5226): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Process (  971): killProcessQuiet, pid=5194
I/ActivityManager(  971): Killing 5194:com.htc.android.mail:sync/u0a62 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/GLSUser ( 1885): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1885): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1885): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1885): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  971): Recipient 5194
,D/WifiService(  971): Client connection lost with reason: 4
,I/ActivityManager(  971): Waited long enough for: ServiceRecord{32231793 u0 com.htc.club/com.mcrm.autonotification.NotificationService}
,V/GLSActivity( 1885): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5674): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5674): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5674): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5674): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/Finsky  ( 5674): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive,
,D/Process (  971): killProcessQuiet, pid=5096
I/ActivityManager(  971): Killing 5096:com.htc.bgp/u0a11 (adj 15): empty #17
,D/DeviceConnectionService( 1780): client connected with version: 7571000
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5096
,D/Process (  971): killProcessQuiet, pid=5265,
I/ActivityManager(  971): Killing 5265:com.htc.task.gtask/u0a66 (adj 15): empty #18
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5265
,I/GAV2    ( 5526): Thread[GAThread,5,main]: No campaign data found.,
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4384, uid=10024, userID:0,
I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4384, uid=10024, userID:0
,I/PackageManager(  971):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4384, uid=10024, userID:0
I/CheckinService( 4384): Done disabling old GoogleServicesFramework version,
,D/AutoSetting( 1421): service - handleMessage() stop self,
,D/AutoSetting( 1421): service - handleMessage() quit looper,
D/AutoSetting( 1421): service - onDestroy() END
,I/HtcModeClient( 3273): handler message = 4011,
E/HtcModeClient( 3273): Check connection and retry 7 times.
,D/Process (  971): killProcessQuiet, pid=5403
,I/ActivityManager(  971): Killing 5403:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5403
,D/Process (  971): killProcessQuiet, pid=5445
,I/ActivityManager(  971): Killing 5445:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5445
,W/MediaManager( 5173): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  971): killProcessQuiet, pid=5311,
I/ActivityManager(  971): Killing 5311:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/HtcModeClient( 3273): handler message = 4011
,E/HtcModeClient( 3273): Check connection and retry 8 times.
,I/ActivityManager(  971): Recipient 5311
,D/Process (  971): killProcessQuiet, pid=5296
I/ActivityManager(  971): Killing 5296:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5296,
,I/ActivityManager(  971): Waited long enough for: ServiceRecord{17c13bea u0 com.htc.musicenhancer/.EnhancerService},
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/HtcModeClient( 3273): handler message = 4011,
E/HtcModeClient( 3273): Check connection and retry 9 times.
,D/PMS     (  971): acquireWL(21944e9a): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10072}
V/AlarmManager(  971): sending alarm PendingIntent{213493cb: PendingIntentRecord{26cf7a8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457596490648, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{2fcad2c1: PendingIntentRecord{27d8ba66 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=86136, Int=0
,V/AlarmManager(  971): sending alarm PendingIntent{10f6a1a7: PendingIntentRecord{c6de654 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=86499, Int=0
,D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  971): releaseWL(21944e9a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  971): [NET] android_getaddrinfofornet-, err=8
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  971): [NET] android_getaddrinfo_proxy+
D/libc    (  971): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    (  971): [NET] android_getaddrinfo_proxy-, NODATA
,D/Finsky  ( 5674): [572] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5674): [1] 5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC <<,
,I/HtcModeClient( 3273): handler message = 4011,
E/HtcModeClient( 3273): Check connection and retry 10 times.
,I/HtcModeClient( 3273): handler message = 4011,
E/HtcModeClient( 3273): Check connection and retry 11 times.
,D/PMS     (  971): acquireWL(3ff0d9fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000},
,V/AlarmManager(  971): sending alarm PendingIntent{636afb: PendingIntentRecord{2e0f3718 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=97125, Int=0
,D/PMS     (  971): releaseWL(3ff0d9fd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/ClockController( 1222): schedule update now=1457596500061 next=59939
,I/Clock   ( 1222): updateClock:08:55 Europe/Warsaw
I/Clock   ( 1222): updateClock:08:55 Europe/Warsaw
,I/Clock   ( 1222): updateClock:08:55 Europe/Warsaw
,D/PMS     (  971): acquireWL(32a616f2): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10024}
,V/AlarmManager(  971): sending alarm PendingIntent{1ce1b143: PendingIntentRecord{ce9cba6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=99305, Int=0
,D/PMS     (  971): acquireWL(2ced13c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1885 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(32a616f2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1885): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1885): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1885): [NET] android_getaddrinfo_proxy+
D/libc    ( 1885): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1885): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  971): releaseWL(2ced13c0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(1b764bb5): PARTIAL_WAKE_LOCK  Icing 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(1b764bb5): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): acquireWL(137605bb): PARTIAL_WAKE_LOCK  Icing 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(137605bb): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  971): acquireWL(19913c6d): PARTIAL_WAKE_LOCK  Icing 0x1 4384 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(19913c6d): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/HtcModeClient( 3273): handler message = 4011,
E/HtcModeClient( 3273): Check connection and retry 12 times.
,I/HtcModeClient( 3273): handler message = 4011
,E/HtcModeClient( 3273): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3273): Don't start project servcice
,D/HtcModeClient( 3273): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3273): connectState: CONNECTION_READY = false
,D/SilentMusic( 3273): call stop
D/HtcModeClient( 3273): close connection
W/HtcModeClient( 3273): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3273): read the terminate packet, so break,
I/ActivityManager(  971): Killing 3273:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=3273
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 3273
,I/ActivityManager(  971): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=5870 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  971): acquireWL(c8e20a2): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10076},
V/AlarmManager(  971): sending alarm PendingIntent{5c17133: PendingIntentRecord{244cecf0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457596510745, Int=60000
D/PMS     (  971): releaseWL(c8e20a2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076},
,D/SMSBackup( 5870): SMSBackupAgentService started,
D/SMSBackup( 5870): Checking restore status
,D/SMSBackup( 5870): Restore complete,
D/SMSBackup( 5870): cancelCheckAlarm
,D/SMSBackup( 5870): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  971): killProcessQuiet, pid=5371
I/ActivityManager(  971): Killing 5371:com.htc.sdm/u0a79 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5371
,I/PMS     (  971): Going to sleep due to screen timeout (uid 1000)...
,I/SensorManager(  971): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@39e51ce3,
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/PMN     (  971): goingToSleep
W/SensorService(  971): disable: get sensor name = Accelerometer Sensor
W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 4
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  971): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@39e51ce3, eanble = 0, strlen(mName) = 91
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  971): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@20b44e5f
W/SensorService(  971): Listener[1] = com.htc.smartdim.sensor_eye@2aaaca2c
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/HtcLockScreen( 1222): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  971): mWirelessDisplayManager is null
W/PMS     (  971): mWirelessDisplayManager is still null
,D/PMS     (  971): acquireWL(dd1a4ee): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 971 1000 null
,W/PMN     (  971): goingToSleep done
,I/PMS     (  971): Sleeping (uid 1000)...
D/XAN-DPS (  971): prepareColorFade 1
,W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,I/Adreno-EGL(  971): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  971): OpenGL ES Shader Compiler Version: E031.25.03.01,
I/Adreno-EGL(  971): Build Date: 03/09/15 Mon
I/Adreno-EGL(  971): Local Branch: 
I/Adreno-EGL(  971): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  971): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  971):                  d74aa161a12b9c6fc6332151
I/ActivityManager(  971): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5892 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
D/PMS     (  971): releaseWL(dd1a4ee): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  971): ACTION_SCREEN_ON
,I/AlarmManager(  971): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  971): [AlarmQueuing] done recovering
I/AlarmManager(  971): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  971): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiStateMachine(  971): handleMessage: E msg.what=131167
E/WifiStateMachine(  971): processMsg: InitialState
,E/WifiStateMachine(  971):  InitialState CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_SCREEN_STATE_CHANGED 1 0
,E/WifiStateMachine(  971):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState,
,D/WifiStateMachine(  971): getWifiLinkLayerStats: WIFI is not enbled
,D/WifiStateMachine(  971): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  971): handleScreenStateChanged Exit: true
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131154
E/WifiStateMachine(  971): processMsg: InitialState
E/WifiStateMachine(  971):  InitialState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131127
E/WifiStateMachine(  971): processMsg: InitialState
,E/WifiStateMachine(  971):  InitialState !CMD_ENABLE_ALL_NETWORKS 0 0,
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131129
E/WifiStateMachine(  971): processMsg: InitialState
E/WifiStateMachine(  971):  InitialState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  971): handleMessage: X
V/SRS_Proc(  407): ParamSet string: screen_state=on
,E/audio_a2dp_hw(  407): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  971): handleMessage: E msg.what=155650
D/WifiController(  971): processMsg: ApStaDisabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/NetworkPolicy(  971): updateScreenOn: false
V/NetworkPolicy(  971): updateIfacesLocked()
,D/NetworkManagementService(  971): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/ResourcesManager( 5892): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/CalendarProvider2( 5892): Created com.android.providers.calendar.CalendarAlarmManager@29ba95c4(com.htc.providers.calendar.HtcCalendarProvider@37abacad)
,I/IntentController( 1222): receive(android.intent.action.SCREEN_ON,1,false),
,D/CalendarProvider2( 5892): wait start:true
,D/PMS     (  971): acquireWL(ec90d23): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  971): acquireWL(2c5f87d9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(ec90d23): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(2c5f87d9): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  971): prepareColorFade done
,D/XAN-DPS (  971): setBrightness to 0
,D/AlarmManager(  971): ACTION_SCREEN_OFF
,I/SensorManager(  971): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@20b44e5f
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  971): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
I/AlarmManager(  971): [AlarmQueuing] screen off now: 
D/WifiDataStallTracker(  971): stopDataStallAlarm 
I/AlarmManager(  971): [AlarmQueuing] data connection: true
E/WifiDataStallTracker(  971): ENABLE_DATA_MONITOR_POLL false Token 0
I/AlarmManager(  971): [AlarmQueuing] wifi connection: false
E/WifiStateMachine(  971): handleMessage: E msg.what=131167
V/ActivityManager(  971): Display changed displayId=0
E/WifiStateMachine(  971): processMsg: InitialState
D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
E/WifiStateMachine(  971):  InitialState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  971):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state InitialState suppState:UninitializedState
D/WifiStateMachine(  971): getWifiLinkLayerStats: WIFI is not enbled
E/WifiStateMachine(  971): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  971): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  971): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131154
E/WifiStateMachine(  971): processMsg: InitialState
W/SensorService(  971): pid=971, uid=1000
W/SensorService(  971): Active sensors: size = 3
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@20b44e5f, eanble = 0, strlen(mName) = 67
E/WifiStateMachine(  971):  InitialState CMD_ENABLE_RSSI_POLL 0 0
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  971): Listener[0] = com.htc.smartdim.sensor_eye@2aaaca2c
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  971): handleMessage: X
E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
V/SRS_Proc(  407): ParamSet string: screen_state=off
E/audio_a2dp_hw(  407): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  971): handleMessage: E msg.what=155651
D/WifiController(  971): processMsg: ApStaDisabledState
D/WifiController(  971): processMsg: DefaultState
,D/WifiController(  971): handleMessage: X
D/CalendarProvider2( 5892): wait end:false
D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/NetworkPolicy(  971): updateScreenOn: false
V/NetworkPolicy(  971): updateIfacesLocked()
D/NetworkManagementService(  971): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/ActivityManager(  971): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5921 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/SensorManager( 1222): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@248c73c5, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  971): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  971): pid=1222, uid=10041
W/SensorService(  971): Active sensors: size = 4
W/SensorService(  971): Accelerometer Sensor (handle=0x00000000, connections=1),
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@248c73c5, eanble = 1, strlen(mName) = 57
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  971): Listener[0] = com.htc.smartdim.sensor_eye@2aaaca2c
W/SensorService(  971): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@248c73c5
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] getTotalRam: 1842 Mb
,I/IntentController( 1222): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1457): start background delete task...,
,D/PMS     (  971): acquireWL(347904c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(347904c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(1a37c895): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1780 10024 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1457): size: 0 , 0
D/ContactMessageStore( 1457): Background delete complete
W/ContextImpl( 5921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  971): releaseWL(1a37c895): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 5921): MY_DEBUG = false
,W/ContextImpl( 5921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,I/RemoteViews( 1222): setHTCTheme(com.htc.updater,true,33751145),
,I/RemoteViews( 1222): apply : com.htc.updater 1 11 2 36
,D/PMS     (  971): acquireWL(18836538): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5921 1000 null,
,D/SmartSyncUtils( 5921): isEpsOn(), nState = 0,
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2,
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/SurfaceControl(  971): Excessive delay in setPowerMode(): 286ms,
D/PMS     (  971): Setting HAL interactive mode to false
,D/PMS     (  971): Setting HAL interactive mode to false done,
D/PMS     (  971): Setting HAL auto-suspend mode to true
D/PMS     (  971): Setting HAL auto-suspend mode done
D/HABCtrl (  971): TPE algorithm. remove timeout.
,I/InputManager(  971): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  971): OOBE c monitor 11
I/InputMethodManagerService(  971): screenObserver, isScreenOn=false
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
,I/InputMethodManagerService(  971): Disable input method client, pid=3223
,I/IntentController( 1222): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1476): ScreenObserver: OFF
D/NfcService( 1476): applyRouting - 0
,D/PMS     (  971): acquireWL(3a195911): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(3a195911): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  971): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: ApStaDisabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  971): << updateStatus
,I/art     (  971): Explicit concurrent mark sweep GC freed 23069(1125KB) AllocSpace objects, 2(196KB) LOS objects, 33% free, 18MB/27MB, paused 1.379ms total 162.518ms
,D/NfcService( 1476): applyRouting -2
D/PMS     (  971): acquireWL(2a144a76): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1476 1027 null
,D/NfcService( 1476): applyRouting
D/NfcService( 1476): Ignore this applyRouting...
,D/PMS     (  971): releaseWL(2a144a76): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMS     (  971): releaseWL(18836538): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/SmartDim(  971): Init customizeScreenOffDelayClass error
W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false),
D/PowerUI ( 1222): closing low battery warning: level=100
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/ClockController( 1222): stop clock update:screen off
I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 5921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5921): isEpsOn(), nState = 0,
D/SmartSyncUtils( 5921): isEpsOn(), nState = 0
,W/ContextImpl( 5921): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  971): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2aaaca2c
,W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  971): pid=971, uid=1000
,W/SensorService(  971): Active sensors: size = 3
W/SensorService(  971): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaaca2c, eanble = 0, strlen(mName) = 36
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  971): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@248c73c5
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/SensorService(  971): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  971): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  971): pid=971, uid=1000,
W/SensorService(  971): Active sensors: size = 2
W/SensorService(  971): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  971): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  971): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@2aaaca2c, eanble = 0, strlen(mName) = 36
W/SensorService(  971): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  971): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@248c73c5
W/SensorService(  971): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  971): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@2aaaca2c
,I/PowerUsageList:PowerUsageHelper( 5921): PowerProfile::POWER_SCREEN_FULL = 154.8
E/ActivityThread(  971): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3e59acf5 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  971): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3e59acf5 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  971): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  971): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  971): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  971): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  971): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  971): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  971): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  971): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  971): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  971): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  971): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  971): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  971): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  971): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  971): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  971): 	,at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  971): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5955 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/PowerUsageList:BatterySipperExt( 5921): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageService( 5921): calcPower(), no data,
,D/PowerUsageList:PowerUsageHelper( 5921): MY_DEBUG = false,
,I/ActivityManager(  971): Killing 5627:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,D/Process (  971): killProcessQuiet, pid=5627
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/SmartSyncUtils( 5921): getMobilePolicyEnabled, result = true
,D/WifiService(  971): New client listening to asynchronous messages,
E/WifiTrafficPoller(  971): ADD_CLIENT: 7
,I/ActivityManager(  971): Recipient 5627,
,D/Process (  971): killProcessQuiet, pid=5649
,I/ActivityManager(  971): Killing 5649:com.android.settings/1000 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5649
,I/CalendarProvider2( 5892): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5892): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 5781): ---------------------------------------------------,
D/ProviderChangeReceiver( 5781): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
I/ActivityManager(  971): Killing 5743:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/HtcAlertService( 5781): start to updateAlertNotification!
D/Process (  971): killProcessQuiet, pid=5743,
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  971): Recipient 5743
,D/HtcAlertService( 5781): No fired or scheduled alerts,
D/HtcAlertUtils( 5781): -- cancelReminderNotification --
D/HtcAlertUtils( 5781): broadcastExistReminder!
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  971): releaseWL(1adfeaf): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,D/HtcUPManager( 1222): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1457): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  971): acquireWL(29a9754d): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{1000}
,V/AlarmManager(  971): sending alarm PendingIntent{25729802: PendingIntentRecord{2fa78513 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1457596527888, Int=0
D/PMS     (  971): acquireWL(1491a350): PARTIAL_WAKE_LOCK  *backup* 0x1 971 1000 null
,D/PMS     (  971): releaseWL(29a9754d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/BackupManagerService(  971): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
E/BackupManagerService(  971): Requested init for com.google.android.gms.backup.BackupTransportService but not found,
D/PMS     (  971): releaseWL(1491a350): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,D/Process (  971): killProcessQuiet, pid=5346,
I/ActivityManager(  971): Killing 5346:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5346
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  971): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  971): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  971): acquireWL(1a51949): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{1000}
,V/AlarmManager(  971): sending alarm PendingIntent{10f6a1a7: PendingIntentRecord{c6de654 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=147800, Int=0
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,V/AlarmManager(  971): sending alarm PendingIntent{636afb: PendingIntentRecord{2e0f3718 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157124, Int=0
D/libc    (  971): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  971): sending alarm PendingIntent{1876324e: PendingIntentRecord{23fb5f6f android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=161686, Int=0
,D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  971): [NET] android_getaddrinfo_proxy+
D/libc    (  971): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  971): [NET] android_getaddrinfo_proxy-, NODATA
,V/AlarmManager(  971): sending alarm PendingIntent{27f5a47c: PendingIntentRecord{f9d0105 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143521, Int=0,
,V/AlarmManager(  971): sending alarm PendingIntent{b07255a: PendingIntentRecord{ce9cba6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=158661, Int=0
,D/PMS     (  971): acquireWL(1d08838b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1885 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1885): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1885): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1885): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1885): [NET] android_getaddrinfo_proxy+
D/libc    ( 1885): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1885): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  971): releaseWL(1d08838b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(1a51949): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  971): acquireWL(3d368c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  971): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): releaseWL(3d368c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
,D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: ApStaDisabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1457): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,TIME-OUT KILL (timeout was 150000ms)
```
