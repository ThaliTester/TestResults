#### Test 50388019809f971_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/Process (  908): killProcessQuiet, pid=2609
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
--------- beginning of /dev/log/system
I/ActivityManager(  908): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3000 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  908): Killing 2609:com.htc.lmw/u0a59 (adj 15): empty #17
D/ResetNotifyBootCompleteReceiver( 1215): Receive bootcomplete intent
,W/ContextImpl( 1215): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
I/ActivityManager(  908): Recipient 2609
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcCupdXmlParser( 3000): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3017 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ActivityThread( 3000): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
I/dalvikvm-heap( 1215): Grow heap (frag case) to 12.394MB for 2097144-byte allocation
D/AppTag  ( 3017): getInstance(Context context)
D/AppTag  ( 3017): getInstance(Context context)
D/AppTag  ( 3017): onCreate()
D/QXDM2SD:HtcNative( 1215): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/HtcCupdXmlParser( 3000): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3033 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  908): killProcessQuiet, pid=2653
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2653:com.htc.reportagent/u0a65 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2653
I/AlarmManager(  908): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  908): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  908): [AlarmQueuing] init alarm queuing list
E/cutils-trace( 3029): Error opening trace file: No such file or directory (2)
V/Settings:HtcSettingsApplication( 3033): [3033/3033] onCreate()
W/ContextImpl( 3033): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3052 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3065 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  908): killProcessQuiet, pid=2703
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2703:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/CustomizationManager( 3029): ====startRecUseTime====
D/htc.customization.log.level( 3029):  is 
W/CustomizationLogLevel( 3029): Level value is invalid, use default level 2
I/ActivityManager(  908): Recipient 2703
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4267b520
D/HtcFingerPrintQuickLaunchProvider( 3065): -onCreate()
I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@423b9ef8
V/Settings:HtcSettingsApplication( 3065): [3065/3065] onCreate()
D/Process (  908): killProcessQuiet, pid=2671
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/CustomizationManager( 3029):  Read ACC file spent 0.049 (s)
I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@423e1740
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  908): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.android.mail
W/ContextImpl( 3065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  908): Killing 2671:com.android.vending/u0a73 (adj 15): empty #17
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3029): Parsing tag item name = HTC__031
D/Process (  908): killProcessQuiet, pid=2719
V/CustomizationCIDLoader( 3029): full path : /system/customize/CID/HTC__032.xml
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CustomizationCIDLoader( 3029): Parsing tag category name = system
I/CustomizationCIDLoader( 3029): Parsing tag category name = application
I/CustomizationCIDLoader( 3029): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3029): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3029): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3029): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3029): Parsing tag category name = Settings
D/CustomizationManager( 3029):  Read CID file spent 0.096 (s)
D/CustomizationManager( 3029):  All configurations done spent 0.096 (s)
I/ActivityManager(  908): Killing 2719:com.htc.showme/u0a82 (adj 15): empty #17
I/ActivityManager(  908): Resuming delayed broadcast
W/HtcNativeFlag( 3029): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3029): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3029): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3029): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  908): Recipient 2719
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TetherSettings( 3065): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3065): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3065): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3065): Cust_ConnectToPC   : spcsc>false
D/        ( 3065): Cust_ConnectToPC   : IPT>true
D/        ( 3065): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3065): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/GAV2    ( 2769): Thread[GAThread,5,main]: No campaign data found.
D/TetherSettings( 3065): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3065): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3065): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3065): Cust_ConnectToPC   : spcsc>false
D/        ( 3065): Cust_ConnectToPC   : IPT>true
D/        ( 3065): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3065): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3065): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3065): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3065): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 3065): setISNotification
D/SmartNS_Utility( 3065): usb_cable_connect = 1
D/SmartNS_Utility( 3065): usb_denied = 0
I/SmartNS_PSService( 3065): usb notificaiton:true
V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3065/1000)
D/SmartNS_Utility( 3065): usb_cable_connect = 1
D/SmartNS_Utility( 3065): usb_denied = 0
I/SmartNS_PSService( 3065): usb notificaiton:true
V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3065/1000)
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  908): Recipient 2671
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
W/asset   (  908): Copying FileAsset 0x6c053138 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1112839176
D/Process (  908): killProcessQuiet, pid=2739
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3029
D/PMS     (  908): acquireHCC(42699ea0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(42700c40): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
D/PMS     (  908): acquireWL(42792c30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/ActivityManager(  908): Killing 2739:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b9d788
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
I/RemoteViews( 1107): com.android.settings (true,33751552)
D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41d6d700 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/RemoteViews.Performance( 1107): com.android.settings 3 8 1 10
I/RemoteViews( 1107): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1107): com.android.settings 0 1 10
I/ActivityManager(  908): Recipient 2739
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3086 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/ActivityManager(  908): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3098 uid=9987 gids={49987}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42429198, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42429198, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b8d658
W/SensorService(  908): Listener[1] = com.android.server.power.DisplayPowerController$10@420f7828
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@42429198
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/asset   ( 3086): Copying FileAsset 0x5c83a428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42429198, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{4279a680 u0 ReceiverList{4279a578 908 system/1000/u0 local:4272a310}}
I/TrimMemoryManager( 1248): [trimMemory] 20
D/NfcUiccLockService( 3098): -- To check whether previous opened channel needed to be closed ...
V/WebViewChromiumFactoryProvider( 3086): Binding Chromium to main looper Looper (main, tid 1) {41aafe40}
I/LibraryLoader( 3086): Expected native library version number "",actual native library version number ""
I/chromium( 3086): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3086): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(4235ff98): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): acquireWL(42459520): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): releaseWL(42459520): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  908): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3115 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
D/Process (  908): killProcessQuiet, pid=2784
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2784:com.google.android.partnersetup/u0a31 (adj 15): empty #17
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 3
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42429198, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b8d658
W/SensorService(  908): Listener[1] = com.android.server.power.DisplayPowerController$10@420f7828
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@42429198
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42415798:true
D/BluetoothAdapter( 3086): 1101815136: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  908): Recipient 2784
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Adreno-EGL( 3086): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3086): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3086): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3086): Local Branch: 
I/Adreno-EGL( 3086): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3086): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3086):                  aa63bbd948f41d15fc72f585e
W/chromium( 3086): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
V/AlarmManager(  908): sending alarm PendingIntent{41f94250: PendingIntentRecord{42536510 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21183, Int=1800000
V/AlarmManager(  908): sending alarm PendingIntent{4231db50: PendingIntentRecord{41d61d90 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=49197, Int=259200000
V/AlarmManager(  908): sending alarm PendingIntent{41dccd30: PendingIntentRecord{4240a7b8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50288, Int=0
W/dalvikvm( 3086): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3086): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
V/AlarmManager(  908): sending alarm PendingIntent{4249ade8: PendingIntentRecord{424e20d0 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448708400000, Int=86400000
W/dalvikvm( 3086): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3086): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3086): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3086): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3086): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3086): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3086): CordovaWebView is running on device made by: HTC
D/Process (  908): killProcessQuiet, pid=2837
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3144 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 2837:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2837
D/PMS     (  908): releaseWL(42730918): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
W/AwContents( 3086): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +322ms
W/ResourceType( 3086): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3086): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41af70e8, mServedView=org.apache.cordova.engine.SystemWebView{41abd080 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3086): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1248
I/InputMethodManagerService(  908): Enable input method client, pid=3086
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  908): releaseWL(42792c30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/YouTube ( 3144): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 3144): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3144): [NET] getaddrinfo-, SUCCESS
I/chromium( 3086): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/YouTube ( 3144): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
E/AndroidProtocolHandler( 3086): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 3086): Set native->JS mode to OnlineEventsBridgeMode
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (3144/10168)
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3144): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3144): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3144): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/jxcore_app_log( 3086): JniHelper::setJavaVM(0x4158a048), pthread_self() = 1658052336
D/JX-Cordova( 3086): jxcore cordova android initializing
D/YouTube ( 3144): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.htc.aurora
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
W/jxcore-log( 3086): Initializing JXcore engine
W/jxcore-log( 3086): JXcore engine is ready
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
E/ExternalAccountType( 1308): Unsupported attribute readOnly
W/jxcore-log( 3086): Starting JXcore engine
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
D/YouTube ( 3144): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
D/PhoneApp( 1215): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
D/MediaRouterService(  908): Client com.google.android.youtube (pid 3144): Registered
I/MediaRouter( 3144): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
D/YouTube ( 3144): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3144): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448709347&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.youtube (3144/10168)
D/libc    ( 3144): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3144): [NET] getaddrinfo-,err=8
D/libc    ( 3144): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3144): [NET] getaddrinfo-, 1
D/libc    ( 3144): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 3144): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 3144): Error sending ping
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3144): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3144): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/MediaRouter( 3144): getSelectedRoute
D/YouTube ( 3144): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3144): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (3144/10168)
W/BroadcastQueue(  908): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/YouTube ( 3144): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3144): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3144): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
D/AutoSetting( 1372): receiver - intent: android.intent.action.USER_PRESENT
D/Process (  908): killProcessQuiet, pid=2857
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1372): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3065): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3065): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3065): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3065): Cust_ConnectToPC   : spcsc>false
D/        ( 3065): Cust_ConnectToPC   : IPT>true
D/        ( 3065): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3065): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3065): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3065): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3065): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3065): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  908): Killing 2857:com.htc.mobiledata/u0a91 (adj 15): empty #17
W/ContextImpl( 3065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Recipient 2857
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 3086): Platform android
W/jxcore-log( 3086): 
W/jxcore-log( 3086): Process ARCH arm
W/jxcore-log( 3086): 
I/jxcore-log( 3086): JXcore Cordova bridge is ready!
I/jxcore-log( 3086): 
W/jxcore-log( 3086): JXcore engine is started
E/jxcore-log( 3086): >> HTC-HTC Desire 820
E/jxcore-log( 3086): 
I/jxcore-log( 3086): Total memory 1964650496
I/jxcore-log( 3086): 
I/jxcore-log( 3086): Free memory 691081216
I/jxcore-log( 3086): 
I/jxcore-log( 3086): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3086): 
I/jxcore-log( 3086): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3086): 
I/jxcore-log( 3086): userPath [ 'www' ]
I/jxcore-log( 3086): 
I/jxcore-log( 3086): Size 720 1184
I/jxcore-log( 3086): 
I/jxcore-log( 3086): Screen Brightness 10
I/jxcore-log( 3086): 
E/jxcore-log( 3086): Dummy Error Log.
E/jxcore-log( 3086): 
I/SmartNS_PSService( 3065): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3065): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3065):  defaultType:0
I/ActivityManager(  908): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3209 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/browser ( 3209): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3209): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3209): Loading: swewebviewchromium
I/LibraryLoader( 3209): Time to load native libraries: 30 ms (timestamps 7926-7956)
I/LibraryLoader( 3209): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3209): Initializing chromium process, renderers=9
I/LibraryLoader( 3209): Expected native library version number "",actual native library version number ""
I/chromium( 3209): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
W/PackageManager(  908): Unable to load service info ResolveInfo{426821c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
W/chromium( 3209): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/Adreno-EGL( 3209): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3209): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3209): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3209): Local Branch: 
I/Adreno-EGL( 3209): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3209): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3209):                  aa63bbd948f41d15fc72f585e
D/Process (  908): killProcessQuiet, pid=2259
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1273): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  908): Killing 2259:com.android.defcontainer/u0a19 (adj 15): empty #17
I/SIMStateChangeReceiver( 1483): SIM state: ABSENT
I/SIMStateChangeReceiver( 1483): phoneType = 0
I/SIMStateChangeReceiver( 1483): remove notification
I/ActivityManager(  908): Recipient 2259
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3250 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  908): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3262 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=2869
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2869:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2869
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2632): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2632): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2632): onReceive()
D/ExchangePolicystatus( 2632): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2632): onReceive(): else
,D/Process (  908): killProcessQuiet, pid=2901
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1215): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  908): Killing 2901:com.google.android.gm/u0a107 (adj 15): empty #17
,W/WeatherUtility( 1107): can't get weather sync account
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3278 uid=10038 gids={50038}
,W/WeatherRequest( 1107): request cur loc, but there is no sys cur
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,W/AccTypeManager( 3262): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3262): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  908): Recipient 2901
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 3262): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3295 uid=10077 gids={50077}
D/Process (  908): killProcessQuiet, pid=2931
I/jxcore-log( 3086): getBuffer is called!!!!
I/jxcore-log( 3086): 
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2931:com.htc.backup/1000 (adj 15): empty #17
,E/ExternalAccountType( 3262): Unsupported attribute readOnly
,D/SMSBackup( 3295): Got a database change event
,W/AccTypeManager( 3262): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3262): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 3262): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Process (  908): killProcessQuiet, pid=2884
I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3307 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Killing 2884:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ExternalAccountType( 3262): Unsupported attribute readOnly
,I/ActivityManager(  908): Recipient 2931
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 3307): onCreate
D/ProviderChangeReceiver( 3307): ---------------------------------------------------
,D/ProviderChangeReceiver( 3307): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3307): start to updateAlertNotification!
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AlertService( 3307): No fired or scheduled alerts
,D/HtcAlertUtils( 3307): -- cancelReminderNotification --
W/ContextImpl( 3033): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/HtcAlertUtils( 3307): broadcastExistReminder!
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Recipient 2884
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3323 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=2954
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2954:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3338 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3323): can't get weather sync account
,W/WeatherRequest( 3323): request cur loc, but there is no sys cur
,W/Settings( 3323): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3338): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3338): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3338): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  908): Recipient 2954
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 0 8 17
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3352 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2981
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2981:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2981
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4260d0d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3352 10070 null
,D/PMS     (  908): acquireWL(41d2a960): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3352 10070 null
,D/PMS     (  908): releaseWL(4260d0d8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3352): update TASK shortcut>
,I/TodoTaskNotifyService( 3352): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): releaseWL(41d2a960): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,W/NotifyReceiver( 3352): stopSelfResult true
,D/Process (  908): killProcessQuiet, pid=3000
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3367 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  908): Killing 3000:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3000
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3379 uid=10081 gids={50081, 3003, 5012}
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(42699ea0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(42700c40): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/Process (  908): killProcessQuiet, pid=3052
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Process (  908): killProcessQuiet, pid=3017
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
I/ActivityManager(  908): Killing 3052:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  908): Killing 3017:com.zoodles.kidmode/u0a149 (adj 15): empty #18
,D/SMSBackup( 3295): Got a database change event
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3052
I/ActivityManager(  908): Recipient 3017
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3391 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ImageRamCache( 3391): create image Cache, size: 31457280.
I/ImageRamCache( 3391): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3391): create image Cache, size: 12582912.
,I/FeedSettings( 3391): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3391): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3391): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3391): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3391): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3391): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3391): [custom highlight] onReceive
,D/CustomHighlightService( 3391): [custom highlight] onHandleIntent
,I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3391): set custom highlight []
,D/CustomHighlightService( 3391): [custom highlight] set tags 
,D/Process (  908): killProcessQuiet, pid=3098
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3098:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b45050 +
,I/Prism.WidgetManager( 1248): onLoadItems() +
I/ActivityManager(  908): Recipient 3098
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/MessagingShortcutReceiver( 2632): keep hiding shortcut bubble
D/MessagingShortcut( 2632): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2632): After query: 0
D/MessagingShortcut( 2632): mPresentUnreadCount: -1
,D/MessagingShortcut( 2632): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2632): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1534): [EventService] reorderNotification, total:0
D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3352): update TASK shortcut>
I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1215): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3408 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,D/MessagingNotification( 2632): New incoming message, can't cancel notification now
,D/MessagingNotification( 2632): newMsgCnt: 0, false
I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3422 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3408): [680.1.] 30@-121520 -> 40@-121549
I/ActivityManager(  908): Resuming delayed broadcast
,E/Prism.WidgetManager( 1248): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1248): onLoadItems() -
I/Prism.ItemManager( 1248): loadItems() com.htc.launcher.pageview.WidgetManager@41b45050 -
D/Process (  908): killProcessQuiet, pid=3115
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3434 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/ActivityManager(  908): Killing 3115:com.android.smith/u0a163 (adj 15): empty #17
,D/Process (  908): killProcessQuiet, pid=3144
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3144:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  908): Recipient 3115
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 3434): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3434): MmsConfig.loadMmsSettings
,E/dalvikvm( 3434): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3434): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3434): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3434): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3434): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 2632): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2632): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3434): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3434): MmsConfig.loadFromDatabase
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3144
D/MediaRouterService(  908): Client com.google.android.youtube (pid 3144): Died!
,E/Babel   ( 3434): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3434): MmsConfig.loadFromResources
,E/Babel   ( 3434): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3434): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3434, uid=10111, userID:0
,W/Settings( 3434): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CustomHighlightReceiver( 3391): [custom highlight] onReceive
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3434, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3434, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3434, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3434, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3434, uid=10111, userID:0
D/CustomHighlightService( 3391): [custom highlight] onHandleIntent
,D/NewsDB  ( 3391): set custom highlight []
I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3391): [custom highlight] set tags 
,D/CustomHighlightReceiver( 3391): [custom highlight] onReceive
I/ActivityManager(  908): Resuming delayed broadcast
D/CustomHighlightService( 3391): [custom highlight] onHandleIntent
,D/NewsDB  ( 3391): set custom highlight []
I/ActivityManager(  908): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3391): [custom highlight] set tags 
,D/Process (  908): killProcessQuiet, pid=3065
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3065:com.android.settings/1000 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3065
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1739/10178)
D/MtpReceiver( 2148): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2148): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2148): [MTP][handleMessage][startService]
,I/ProviderInstaller( 3434): Installed default security provider GmsCore_OpenSSL
,D/MtpReceiver( 2148): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2148): [MTP][handleMessage]-
,D/MtpService( 2148): [MTP] startForeground
I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3462 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/MtpService( 2148): updating state; isCurrentUser=true, mMtpLocked=false
,I/RemoteViews( 1107): com.android.providers.media (false,0)
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/MtpDatabase( 2148): TotalSize=1918604,MediaCacheLimit=6000
,I/RemoteViews.Performance( 1107): com.android.providers.media 4 4 10
,I/RemoteViews( 1107): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1107): com.android.providers.media 1 4 15
,D/MtpService( 2148): [isMtpConnected] connected: true
,D/SyncApplication( 3462): Loading default preferences
,W/Resources( 3462): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 3462): Overriding preferences with custom values
,D/SyncApplication( 3462): Updating preferences succeeded
,E/SyncApplication( 3462): Application created.
D/VolumeInfo( 3462): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3462): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3462): Found 0 mount point(s)
,V/VolumeInfo( 3462): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3462): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/Process (  908): killProcessQuiet, pid=3209
,D/VolumeInfo( 3462): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3462): Can not create volume ID for unmounted volume null
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3209:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/PhoneApp( 1215): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1215): -- N1 =0
,D/PhoneApp( 1215): -- N2 =0
,D/PhoneApp( 1215): -- N3 =0
,I/CalendarDefines( 3462): getNewCalendarAuthority()...
,D/SyncApplication( 3462): enableAppOperation()+
,D/SyncApplication( 3462): enableAppOperation()-
,D/HTCUtilities( 3462): isNeorSinged() + 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3462, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3462, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3462): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3462): isNeorSinged() return false
D/CDMountReceiver( 3462): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3462): USB connected to PC
,D/FOTAReceiver( 3462): onReceive() enter 
,D/FOTAReceiver( 3462): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=3250
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Recipient 3209
I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3481 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 3250:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3250
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1215): MSG_NOTIFY_CS_TO_SYNC <<
,D/HtcFingerPrintQuickLaunchProvider( 3481): -onCreate()
,V/Settings:HtcSettingsApplication( 3481): [3481/3481] onCreate()
,D/TetherSettings( 3481): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3481): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3481): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3481): Cust_ConnectToPC   : spcsc>false
D/        ( 3481): Cust_ConnectToPC   : IPT>true
,D/        ( 3481): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3481): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3481): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3481): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3481): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3481): Cust_ConnectToPC   : spcsc>false
D/        ( 3481): Cust_ConnectToPC   : IPT>true
D/        ( 3481): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3481): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3481): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3481): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3481): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3481): usb_cable_connect = 1
,D/SmartNS_Utility( 3481): usb_denied = 0
,I/SmartNS_NSReceiver( 3481): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3481): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3481): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3481): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3481): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3481): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3481):  defaultType:0
,I/SmartNS_PSService( 3481): fail notificaiton:false
,D/SmartNS_Utility( 3481): usb_cable_connect = 1
D/SmartNS_Utility( 3481): usb_denied = 0
,I/SmartNS_PSService( 3481): usb notificaiton:true
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3481/1000)
,D/SmartNS_Utility( 3481): usb_cable_connect = 1
D/SmartNS_Utility( 3481): usb_denied = 0
,I/SmartNS_PSService( 3481): usb notificaiton:true
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/PMS     (  908): releaseWL(4235ff98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  908): bSetPropertyMultiRAB:false
,I/RemoteViews( 1107): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1107): com.android.settings 0 1 10
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3481/1000)
D/SmartNS_Utility( 3481): usb_cable_connect = 1
D/SmartNS_Utility( 3481): usb_denied = 0
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3481): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3481): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/RemoteViews( 1107): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1107): com.android.settings 0 1 10
,W/WeatherUtility( 3323): can't get weather sync account
W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1248): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1248): com.google.android.googlequicksearchbox 3 1 5
,I/ActivityManager(  908): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
,I/RemoteViews( 1248): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1248): pl.k2.droidoaudioteka 0 1 8
W/WeatherRequest( 3323): request cur loc, but there is no sys cur
,W/Settings( 3323): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  908): Resuming delayed broadcast
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 1 6 17
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  908): acquireWL(4262da40): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  908): releaseWL(4262da40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1199): CP2 sync disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3506 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3262
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3262:com.htc.contacts/u0a41 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1372): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1372): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3522 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Recipient 3262
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3522, uid=10073, userID:0
,D/Finsky  ( 3522): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3522/10073)
,D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3522/10073)
,D/Finsky  ( 3522): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3522): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3522): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3522, uid=10073, userID:0
,D/Process (  908): killProcessQuiet, pid=3307
,I/ActivityManager(  908): Killing 3307:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1248): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  908): Recipient 3307
,D/Finsky  ( 3522): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3522): [1] 2.run: Finished loading 1 libraries.
,I/IcingCorporaProvider( 2769): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3522): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  908): Delaying start of: ServiceRecord{42625740 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,W/asset   ( 2769): Copying FileAsset 0x63596df0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2769): UpdateCorporaTask done [took 50 ms] updated apps [took 49 ms] 
,D/Finsky  ( 3522): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3557 uid=10098 gids={50098, 3003, 5012}
,I/HtcModeClient( 1483): handler message = 4011
,E/HtcModeClient( 1483): Check connection and retry 5 times.
,I/DeviceManagement( 3557): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3557 dbg=false s=true
,I/DeviceManagement( 3557): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  908): killProcessQuiet, pid=3033
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3570 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 3033:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3033
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=3338
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3338:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3338
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 3570): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  908): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3590 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3590): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3590): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3590): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3557): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3557): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.location.fused, com.htc.android.htcsetupwizard, com.htc.guide, com.htc.usage, com.htc.drive.activator, com.htc.backup, com.qualcomm.timeservice, com.android.keychain, com.android.CSDFunctionG, com.android.providers.settings, com.htc.lockscreen, com.htc.home.personalize, com.htc.backupreset, com.htc.mirrorlinkserver, com.android.inputdevices, com.htc.feedback, com.htc.autobot.cargps.provider, com.htc.htcpowermanager, android, com.htc.smartdim, com.android.settings, com.qualcomm.privinit, com.htc.checkinprovider, com.htc.cirmodule, com.htc.android.htcloglevel]
,I/DeviceManagement( 3557): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3607 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  908): killProcessQuiet, pid=3367
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3367:com.htc.stock/u0a81 (adj 15): empty #17
,I/DeviceManagement( 3557): WorkflowService: Starting workflow service
I/DeviceManagement( 3557): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ae8928] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3557): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3557): ModelRegistry: Loading model meta data from resources...
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3367
,I/DeviceManagement( 3557): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3557): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3607):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  908): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/DeviceManagement( 3557): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,V/AlarmManager(  908): sending alarm PendingIntent{423fa008: PendingIntentRecord{4234aae0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448709351772, Int=0
,I/ActivityManager(  908): Resuming delayed broadcast
,W/GAV2    ( 3570): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/DeviceManagement( 3557): SessionStateController: Checking invariants...
I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3624 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DeviceManagement( 3557): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3557): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41ae8928]
,I/DeviceManagement( 3557): WorkflowService: Stopping workflow service
D/Process (  908): killProcessQuiet, pid=3379
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3379:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3379
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3522): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3522): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/PMS     (  908): acquireWL(42372cb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3624 10160 null
,D/PMS     (  908): releaseWL(42372cb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  908): acquireWL(4217b4e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3624 10160 null
,D/PMS     (  908): acquireWL(425fed20): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3624 10160 null
,D/PMS     (  908): releaseWL(4217b4e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3624/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3624/10160)
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  908): getAllProviders()=[passive, gps, network]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  908): releaseWL(425fed20): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3278
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3278:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3278
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/ActivityManager(  908): Resuming delayed broadcast
,V/AlarmManager(  908): sending alarm PendingIntent{427a1b00: PendingIntentRecord{427a1ac8 com.google.android.gms startService}}, i=null, t=0, cnt=17060, w=84918423, Int=84918423
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3659 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Settings:HtcWirelessFeatureFlags( 3481): id/is att sku: 99/false
,W/SystemReader( 3481): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3481): Cannot find support_harman, use default value instead
,W/SystemReader( 3481): Cannot find effect_manager_id, use default value instead
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,W/ContextImpl( 3659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/SnetService( 1199): snet destroyed
,E/Settings:HtcWrapHeaderInfo( 3481): no such activity!
,D/PowerUsageService( 3659): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3659): MY_DEBUG = false
D/PMS     (  908): acquireWL(423cf800): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3659 1000 null
,W/WeatherUtility( 1107): can't get weather sync account
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3481): The wrap header doesn't exist in header list.
,D/WeatherUtility( 1372): Weather sync is On
,D/WSP     ( 1372): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherUtility( 3323): can't get weather sync account
,E/Settings:HtcWrapHeaderInfo( 3481): updateDevelopment, bPrefShow = true
W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
W/BatSI   (  908): Couldn't get kernel wake lock stats
,E/Settings:HtcUmcWidgetEnabler( 3481): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportRecentAppsButton]support         :false
W/WeatherRequest( 3323): request cur loc, but there is no sys cur
,W/Settings( 3323): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]support         :false
,W/FingerprintManager( 3481): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
,I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 1 8 17
,E/Settings:HtcVoWifiWidgetEnabler( 3481): isSupportVoWifi: null
E/ActivityThread( 3481): Failed to find provider info for com.htc.vowifi
,W/GLSUser ( 1342): GoogleAccountDataService.getToken()
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1342): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1342): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3522): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3522): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3522): [1] DailyHygiene.reschedule: Scheduling new run in 838 minutes (failures=5)
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3481): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3481): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3481): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3481): [supportHomeButton]support         :false
,W/FingerprintManager( 3481): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3481): isSupportVoWifi: null
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3481): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3685 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/Process (  908): killProcessQuiet, pid=3295
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3295:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3295
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  908): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  908): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 0
W/Settings:Agent(  908): >> traceCallingStack()
,W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 919
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 3(ms)
D/BluetoothManagerService(  908): Message: MESSAGE_DISABLE
,D/WifiManager( 3086): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 0
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1247
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  908): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
,W/Settings:Agent(  908): << traceCallingStack(): 2(ms)
,I/jxcore-log( 3086): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 3086): 
,I/jxcore-log( 3086): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3086): 
D/WifiService(  908): setWifiEnabled: false pid=3086, uid=10355
,E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  908): New client listening to asynchronous messages
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/cutils-trace( 3703): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 3703): ====startRecUseTime====
D/htc.customization.log.level( 3703):  is 
,W/CustomizationLogLevel( 3703): Level value is invalid, use default level 2
V/AlarmManager(  908): sending alarm PendingIntent{42455228: PendingIntentRecord{4262d400 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448709353426, Int=0
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3712 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3352
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3352:com.htc.task/u0a70 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3352
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=3408
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3408:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3408
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CustomizationManager( 3703):  Read ACC file spent 0.071 (s)
,D/CIDMapFileReader( 3703): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3703): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3703): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3703): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3703): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3703): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3703): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3703): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3703): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3703): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3703): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3703): Parsing tag category name = system
,I/CustomizationCIDLoader( 3703): Parsing tag category name = application
I/CustomizationCIDLoader( 3703): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3703): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3703): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3703): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3703): Parsing tag category name = Settings
D/CustomizationManager( 3703):  Read CID file spent 0.116 (s)
,D/CustomizationManager( 3703):  All configurations done spent 0.116 (s)
W/HtcNativeFlag( 3703): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3703): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3703): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3703): Fail to get flag for type 'language', use default value: -1
,I/MusicStore( 3712): Database version: 95
,W/ContextImpl( 3712): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3712): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PackageManager(  908): deletePackageAsUser: pkg=com.example.hello, pid=3703, uid=2000 user=0
,I/ActivityManager(  908): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  908): killProcessQuiet, pid=3086,
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  908): Copying FileAsset 0x6c1c43c0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  908): Killing 3086:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  908): Force removing ActivityRecord{426997d0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
,E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,W/InputDispatcher(  908): channel '427a0e60 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  908): channel '427a0e60 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  908): Attempted to unregister already unregistered input channel '427a0e60 com.example.hello.MainActivity (s)'
W/PackageSettings(  908): Skipping PackageSetting{4229b468 com.test.thalitest/10348} due to missing metadata
I/WindowManager(  908): WINDOW DIED Window{427a0e60 u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager(  908): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,D/PMS     (  908): acquireWL(42813230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1417 10028 null
D/DotMatrix( 1534): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1534): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1534): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
W/GeofencerStateMachine( 1417): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1758): Unregistering com.example.hello
E/acms    ( 1758): Could not unregister removed application com.example.hello
I/FeedHostManager( 1248): [onResume]
I/FeedProviderManager( 1248): onResume
I/SocialFeedProvider( 1248): +onResume
I/SocialFeedProvider( 1248): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1248): -onResume
I/Prism.ItemManager( 3391): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3391): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ConnectivityHelper( 1248): [getCurrentConnectionType] no network connection
D/PMS     (  908): releaseWL(42813230): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.launcher (1248/10075)
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3712): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
,D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,E/ExternalAccountType( 1308): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3712): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3712): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 3086 uid 10355
I/InputMethodManagerService(  908): Enable input method client, pid=1248
,W/Binder  ( 1182): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1182): java.lang.NullPointerException
W/Binder  ( 1182): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1182): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1182): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1182): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3712, uid=10154, userID:0
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1215 :
,D/PhoneApp( 1215): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 3712): Registered
,I/MediaRouter( 3712): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3736 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (3712/10154)
,D/MediaRouter( 3712): getSelectedRoute
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3712, uid=10154, userID:0
,D/Process (  908): killProcessQuiet, pid=3422
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Killing 3422:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/DFPI.PIReciver( 3736): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3736): onHandleIntent
,I/DFPI.ApkInstallService( 3736): Media Scan Finished Case 
I/ActivityManager(  908): Recipient 3422
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DFPI.ApkInstallService( 3736): check CID = HTC__032
I/DFPI.ApkInstallService( 3736): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3752 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
,I/ActivityManager(  908): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase,( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3659): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3659): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteDatabase( 3659): Error inserting ...
E/SQLiteDatabase( 3659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3659): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3659): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3659): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3659): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3659): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3659): 	at java.lang.Thread.run(Thread.java:864)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3752/10051)
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/SQLiteLog( 3659): (3850) statement aborts at 34: [SELECT * FROM smartsync_golden_sat ORDER BY date] disk I/O error
E/SQLiteDBG( 3659): func: nativeExecuteForCursorWindow errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca578f8
E/SQLiteQuery( 3659): exception: disk I/O error (code 3850); query: SELECT * FROM smartsync_golden_sat ORDER BY date
W/ContextImpl( 3752): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  908): releaseWL(423cf800): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/PackageManager(  908): Unable to load service info ResolveInfo{4271d7f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SensorManager(  908): mEventCount = 450
,I/SocialFeedProvider( 1248): +disConnect socialManager
,I/SocialFeedProvider( 1248): disconnect socialManager
,I/SocialFeedProvider( 1248): -disConnect socialManager
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3772 uid=10080 gids={50080, 5001, 1028, 1015}
,I/ActivityManager(  908): Killing 3434:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3434
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3772): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3772): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 

```
