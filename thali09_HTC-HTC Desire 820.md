#### Test 50388019f4ce509_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager(  915): sending alarm PendingIntent{4217fab8: PendingIntentRecord{42911030 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=49446, Int=0
,--------- beginning of /dev/log/main
D/Process (  915): killProcessQuiet, pid=2517
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2932 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  915): Killing 2517:com.htc.video/u0a57 (adj 15): empty #17
I/ActivityManager(  915): Recipient 2517
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/GAV2    ( 2697): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 1996): Google Analytics 8.3.01 is starting up.
D/ResetNotifyBootCompleteReceiver( 1227): Receive bootcomplete intent
W/ContextImpl( 1227): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
I/HtcCupdXmlParser( 2932): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  915): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2953 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ActivityThread( 2932): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
I/dalvikvm-heap( 1227): Grow heap (frag case) to 12.404MB for 2097144-byte allocation
D/AppTag  ( 2953): getInstance(Context context)
D/AppTag  ( 2953): getInstance(Context context)
D/AppTag  ( 2953): onCreate()
D/QXDM2SD:HtcNative( 1227): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/ActivityManager(  915): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2970 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/HtcCupdXmlParser( 2932): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
D/Process (  915): killProcessQuiet, pid=2533
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 2533:com.htc.lmw/u0a60 (adj 15): empty #17
I/ActivityManager(  915): Recipient 2533
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 2946): ====startRecUseTime====
D/htc.customization.log.level( 2946):  is 
W/CustomizationLogLevel( 2946): Level value is invalid, use default level 2
I/AlarmManager(  915): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  915): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  915): [AlarmQueuing] init alarm queuing list
D/CustomizationManager( 2946):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2946): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2946): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2946): Parsing tag category name = system
I/CustomizationCIDLoader( 2946): Parsing tag category name = application
I/CustomizationCIDLoader( 2946): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2946): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2946): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2946): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2946): Parsing tag category name = Settings
D/CustomizationManager( 2946):  Read CID file spent 0.095 (s)
D/CustomizationManager( 2946):  All configurations done spent 0.096 (s)
W/HtcNativeFlag( 2946): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2946): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2946): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2946): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  915): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2992 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  915): killProcessQuiet, pid=2638
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 2638:com.htc.reportagent/u0a66 (adj 15): empty #17
V/Settings:HtcSettingsApplication( 2970): [2970/2970] onCreate()
W/ContextImpl( 2970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  915): Recipient 2638
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3005 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/CpuWake (  915): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  915): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  915): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2946
D/PMS     (  915): acquireHCC(428ccdb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 915 1000 null
W/asset   (  915): Copying FileAsset 0x62ce69b0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  915): @test_code: getHtcIntentFlag: 0 obj: 1115617672
D/PMS     (  915): acquireHCC(42895388): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 915 1000 null
D/PMS     (  915): acquireWL(428932f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 915 1000 null
I/FeedHostManager( 1257): [onPause]
I/FeedProviderManager( 1257): onPause
I/FeedHostManager( 1257): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c7c748
E/cutils-trace( 2946): Error opening trace file: No such file or directory (2)
I/SocialFeedProvider( 1257): +onPause
I/SocialFeedProvider( 1257): -onPause
I/AlarmManager(  915): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@423e06f8
I/ActivityManager(  915): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3019 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1257): [trimMemory] 20
I/AlarmManager(  915): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4218fdc8
W/asset   ( 3019): Copying FileAsset 0x5c8d7428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/HtcFingerPrintQuickLaunchProvider( 3005): -onCreate()
I/AlarmManager(  915): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4201df58
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  915): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  915): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  915): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  915): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
D/Process (  915): killProcessQuiet, pid=2655
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
V/Settings:HtcSettingsApplication( 3005): [3005/3005] onCreate()
I/AlarmManager(  915): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  915): Killing 2655:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
W/ContextImpl( 3005): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
D/Process (  915): killProcessQuiet, pid=2667
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
V/WebViewChromiumFactoryProvider( 3019): Binding Chromium to main looper Looper (main, tid 1) {41b3d798}
I/LibraryLoader( 3019): Expected native library version number "",actual native library version number ""
I/ActivityManager(  915): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  915): Killing 2667:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  915): Recipient 2655
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Resuming delayed broadcast
I/chromium( 3019): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3019): Initializing chromium process, renderers=0
D/PMS     (  915): acquireWL(425e34d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/TetherSettings( 3005): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3005): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3005): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3005): Cust_ConnectToPC   : spcsc>false
D/        ( 3005): Cust_ConnectToPC   : IPT>true
D/        ( 3005): Cust_ConnectToPC   : Singel_USB>false
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  915): java.lang.Throwable: stack dump
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  915): acquireWL(425c5460): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  915): releaseWL(425c5460): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  915): Recipient 2667
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BluetoothAdapter( 3019): 1102393744: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42441ae8:true
W/Settings( 3005): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3005): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3005): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3005): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3005): Cust_ConnectToPC   : spcsc>false
D/        ( 3005): Cust_ConnectToPC   : IPT>true
D/        ( 3005): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3005): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3005): hasRemovableStorageSlot: true
I/Adreno-EGL( 3019): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3019): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3019): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3019): Local Branch: 
I/Adreno-EGL( 3019): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3019): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3019):                  aa63bbd948f41d15fc72f585e
D/SmartNS_Utility( 3005): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3005): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 3005): setISNotification
D/SmartNS_Utility( 3005): usb_cable_connect = 1
D/SmartNS_Utility( 3005): usb_denied = 0
I/SmartNS_PSService( 3005): usb notificaiton:true
V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  915): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  915): bSetPropertyMultiRAB:false
D/ConnectivityService(  915): getActiveNetworkInfo called by com.android.settings (3005/1000)
D/SmartNS_Utility( 3005): usb_cable_connect = 1
D/SmartNS_Utility( 3005): usb_denied = 0
I/SmartNS_PSService( 3005): usb notificaiton:true
V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  915): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  915): bSetPropertyMultiRAB:false
D/ConnectivityService(  915): getActiveNetworkInfo called by com.android.settings (3005/1000)
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  915): killProcessQuiet, pid=2682
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/RemoteViews( 1112): com.android.settings (true,33751552)
I/ActivityManager(  915): Killing 2682:com.htc.updater/u0a85 (adj 15): empty #17
D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{41eb6f30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1112): com.android.settings 2 7 1 10
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  915): Recipient 2682
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/chromium( 3019): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  915): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3049 uid=9987 gids={49987}
I/RemoteViews( 1112): com.android.settings (true,33751552)
I/SensorManager(  915): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42643918, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 2
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  915): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42643918, eanble = 1, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  915): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423ef120
W/SensorService(  915): Listener[1] = com.android.server.power.DisplayPowerController$10@421cd248
W/SensorService(  915): Listener[2] = com.htc.smartdim.sensor_eye@42643918
W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/RemoteViews.Performance( 1112): com.android.settings 1 1 10
I/SensorManager(  915): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42643918, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{423f4b38 u0 ReceiverList{422b2b20 915 system/1000/u0 local:4292c208}}
W/dalvikvm( 3019): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3019): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3019): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3019): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3019): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3019): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3019): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3019): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3019): CordovaWebView is running on device made by: HTC
D/NfcUiccLockService( 3049): -- To check whether previous opened channel needed to be closed ...
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 3
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42643918, eanble = 1, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  915): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423ef120
W/SensorService(  915): Listener[1] = com.android.server.power.DisplayPowerController$10@421cd248
W/SensorService(  915): Listener[2] = com.htc.smartdim.sensor_eye@42643918
W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/Process (  915): killProcessQuiet, pid=2712
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3069 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  915): Killing 2712:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  915): Recipient 2712
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3088 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
D/Process (  915): killProcessQuiet, pid=2569
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 2569:com.android.defcontainer/u0a19 (adj 15): empty #17
W/AwContents( 3019): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  915): Recipient 2569
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/InputMethodManagerService(  915): Disable input method client, pid=1257
W/ResourceType( 3019): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3019): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b84518, mServedView=org.apache.cordova.engine.SystemWebView{41b4a4b0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3019): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  915): Enable input method client, pid=3019
I/ActivityManager(  915): Displayed com.example.hello/.MainActivity: +443ms
W/XT9_C   ( 1191): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1191): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1191): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1191): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  915): releaseWL(428932f8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/HtcModeClient( 1492): handler message = 4011
E/HtcModeClient( 1492): Check connection and retry 4 times.
E/YouTube ( 3088): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/chromium( 3019): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3019): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/libc    ( 3088): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3088): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 3088): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/JsMessageQueue( 3019): Set native->JS mode to OnlineEventsBridgeMode
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.youtube (3088/10168)
E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
D/jxcore_app_log( 3019): JniHelper::setJavaVM(0x4160c048), pthread_self() = 1553833608
D/JX-Cordova( 3019): jxcore cordova android initializing
D/YouTube ( 3088): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3088): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3088): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
W/jxcore-log( 3019): Initializing JXcore engine
W/jxcore-log( 3019): JXcore engine is ready
W/jxcore-log( 3019): Starting JXcore engine
D/YouTube ( 3088): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
D/MediaRouterService(  915): Client com.google.android.youtube (pid 3088): Registered
D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
I/MediaRouter( 3088): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/YouTube ( 3088): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
D/ConnectivityService(  915): getNetworkInfo networkType=0 called by com.google.android.youtube (3088/10168)
I/GoogleConversionPing( 3088): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1447834342&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 3088): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3088): [NET] getaddrinfo-,err=8
D/libc    ( 3088): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3088): [NET] getaddrinfo-, 1
D/libc    ( 3088): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3088): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 3088): Error sending ping
E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3088): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3088): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 3088): getSelectedRoute
D/YouTube ( 3088): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/YouTube ( 3088): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.youtube (3088/10168)
I/ActivityManager(  915): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
I/ActivityManager(  915): Resuming delayed broadcast
D/YouTube ( 3088): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/Process (  915): killProcessQuiet, pid=2767
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/YouTube ( 3088): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3088): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/ActivityManager(  915): Killing 2767:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  915): Recipient 2767
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 3019): Platform android
W/jxcore-log( 3019): 
W/jxcore-log( 3019): Process ARCH arm
W/jxcore-log( 3019): 
,I/jxcore-log( 3019): JXcore Cordova bridge is ready!
I/jxcore-log( 3019): 
,W/jxcore-log( 3019): JXcore engine is started
,E/jxcore-log( 3019): >> HTC-HTC Desire 820
E/jxcore-log( 3019): 
,I/jxcore-log( 3019): Total memory 1964650496
I/jxcore-log( 3019): 
I/jxcore-log( 3019): Free memory 691503104
I/jxcore-log( 3019): 
I/jxcore-log( 3019): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3019): 
,I/jxcore-log( 3019): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3019): 
,I/jxcore-log( 3019): userPath [ 'www' ]
I/jxcore-log( 3019): 
,I/jxcore-log( 3019): Size 720 1184
I/jxcore-log( 3019): 
,I/jxcore-log( 3019): Screen Brightness 142
I/jxcore-log( 3019): 
,E/jxcore-log( 3019): Dummy Error Log.
E/jxcore-log( 3019): 
,W/dalvikvm( 1996): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1996): Spent 19ms computing apk sha1.
,D/FileApkUtils( 1996): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1996): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1996): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1996): Beginning GMS chimera module scan
,W/asset   ( 1996): Copying FileAsset 0x6528d718 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
I/ActivityManager(  915): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
W/dalvikvm( 1996): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/ChimeraCfgMgr( 1996): Beginning module configuration check
D/ChimeraCfgMgr( 1996): Module APKs unchanged, check complete
I/ActivityManager(  915): Resuming delayed broadcast
E/dalvikvm( 1996): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1996): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
I/ActivityManager(  915): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1996/10029)
D/PMS     (  915): acquireWL(42951db8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1996 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 1996): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1996): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 1996): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1996): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  915): acquireWL(429542b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1996 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42951db8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1996): COMPAT: Multi user not supported
,D/GCM     ( 1339): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  915): acquireWL(42955048): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1996 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1339/10029)
,I/CheckinService( 1996): Checkin interval check for package: unspecified last checkin: 1447785706304 min interval config: 0 actual interval: 48636331
,I/GCoreUlr( 1996): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1206): DispatchingService.onCreate()
,I/CheckinService( 1996): Disabling old GoogleServicesFramework version
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1996, uid=10029, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1996, uid=10029, userID:0
W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/SystemUpdateService( 1996): onCreate
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1996, uid=10029, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
D/SystemUpdateService( 1996): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1996): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,V/AuthZen ( 1996): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/SystemUpdateService( 1996): cancelUpdate (empty URL)
,I/SystemUpdateService( 1996): active receiver: disabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1996, uid=10029, userID:0
D/PMS     (  915): acquireWL(42962520): PARTIAL_WAKE_LOCK  Icing 0x1 1996 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(42962b90): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1206 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1996, uid=10029, userID:0
W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1996, uid=10029, userID:0
I/CheckinService( 1996): Checking schedule, now: 1447834342702 next: 1448308642842
I/CheckinService( 1996): active receiver: disabled
D/PMS     (  915): releaseWL(42962520): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1996, uid=10029, userID:0
D/AuthZenEventHandler( 1996): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1996, uid=10029, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1996, uid=10029, userID:0
I/GCoreUlr( 1206): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/SystemUpdateService( 1996): onDestroy
D/PMS     (  915): releaseWL(429542b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(42955048): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 1996): Using Auth Proxy for data requests.
,W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1996): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1996): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1206, uid=10029, userID:0
,W/dalvikvm( 1996): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/GCoreUlr( 1206): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1206): Unbound from all location providers
D/PMS     (  915): acquireWL(4297bf50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1206 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(4297bf50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42962b90): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/AuthZen ( 1996): Fetching signing key...
I/ActivityManager(  915): Resuming delayed broadcast
,I/GCoreUlr( 1206): DispatchingService.onDestroy()
,I/GCoreUlr( 1206): Stopping handler for UlrDispSvcFast
,I/AuthZen ( 1996): Signing key fetched successfully!
,I/GCoreUlr( 1206): Unbound from all location providers
D/PMS     (  915): acquireWL(42988a78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1206 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(42988a78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 1996): Using Auth Proxy for data requests.
D/PMS     (  915): acquireWL(4298ae90): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1996 10029 null
I/ActivityManager(  915): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/PMS     (  915): acquireWL(4298ba00): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1996 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(4298ae90): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/AuthZenTransactionCache( 1996): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1996): Clearing transaction cache
D/PMS     (  915): releaseWL(4298ba00): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/jxcore-log( 3019): getBuffer is called!!!!
I/jxcore-log( 3019): 
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  915): Resuming delayed broadcast,
I/GAV2    ( 2829): Thread[GAThread,5,main]: No campaign data found.
,W/Auth    ( 1339): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
D/PMS     (  915): acquireWL(42941548): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1339 10029 null
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  915): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  915): releaseWL(42941548): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,V/GmsCoreStatsServiceLauncher( 1996): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
I/ActivityManager(  915): Resuming delayed broadcast
,D/PersistentNotificationBroadcastReceiver( 1339): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  915): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3181 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(428e9268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(428e9268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3181): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3181, uid=10074, userID:0
,D/Finsky  ( 3181): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  915): getAllNetworkInfo called by com.android.vending (3181/10074)
,W/CpuWake (  915): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  915): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  915): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  915): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  915): <<release mCpuPerf_Freq wakelock
,D/PMS     (  915): releaseHCC(428ccdb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/dalvikvm( 3181): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/PMS     (  915): releaseHCC(42895388): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/dalvikvm( 3181): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  915): getAllNetworkInfo called by com.android.vending (3181/10074)
,D/Finsky  ( 3181): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3181): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3181): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3181): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3181): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3181): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3181): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3181): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3181, uid=10074, userID:0
,D/Volley  ( 3181): [298] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 3181): Skipping gmscore version check
,D/Process (  915): killProcessQuiet, pid=2786
,I/ActivityManager(  915): Killing 2786:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Volley  ( 3181): [291] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager(  915): Recipient 2786
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023786
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024025
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024031
,D/AutoSetting( 1296): receiver - intent: android.intent.action.USER_PRESENT
,D/Finsky  ( 3181): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3181): [1] 2.run: Finished loading 1 libraries.
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028885
D/TetherSettings( 3005): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3005): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3005): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3005): Cust_ConnectToPC   : spcsc>false
D/        ( 3005): Cust_ConnectToPC   : IPT>true
D/        ( 3005): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3005): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3005): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3005): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3005): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1296): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/Finsky  ( 3181): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/PSReceiver( 3005): onReceive:android.intent.action.USER_PRESENT
V/AlarmManager(  915): sending alarm PendingIntent{41fdd408: PendingIntentRecord{42628cb8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21014, Int=1800000
V/AlarmManager(  915): sending alarm PendingIntent{4218d9e8: PendingIntentRecord{4290c120 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=49238, Int=259200000
V/AlarmManager(  915): sending alarm PendingIntent{41d83af0: PendingIntentRecord{424f21d8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50115, Int=0
W/ContextImpl( 3005): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3005): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3005): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3005):  defaultType:0
I/ActivityManager(  915): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  915): Resuming delayed broadcast
,D/Finsky  ( 3181): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  915): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3219 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3219): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3219): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3219): Loading: swewebviewchromium
,I/LibraryLoader( 3219): Time to load native libraries: 39 ms (timestamps 3571-3610)
,I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3219): Initializing chromium process, renderers=9
I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
,I/chromium( 3219): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/chromium( 3219): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3219): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3219): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3219): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3219): Local Branch: 
I/Adreno-EGL( 3219): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3219): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3219):                  aa63bbd948f41d15fc72f585e
,D/Process (  915): killProcessQuiet, pid=2799
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1281): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
,I/ActivityManager(  915): Killing 2799:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/SIMStateChangeReceiver( 1492): SIM state: ABSENT
I/SIMStateChangeReceiver( 1492): phoneType = 0
,I/SIMStateChangeReceiver( 1492): remove notification
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 2799
,I/ActivityManager(  915): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3258 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  915): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3270 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  915): killProcessQuiet, pid=2829
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 2829:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 2829
,D/ContactMessageStore( 1227): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1227): MSG_NOTIFY_CS_TO_SYNC <<
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2590): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2590): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2590): onReceive()
D/ExchangePolicystatus( 2590): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2590): onReceive(): else
,D/Process (  915): killProcessQuiet, pid=2864
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  915): Killing 2864:com.htc.backup/1000 (adj 15): empty #17
D/HtcBroadcastReceiver( 1227): onReceive: android.intent.action.SIM_STATE_CHANGED
,I/ActivityManager(  915): Recipient 2864
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 1112): can't get weather sync account
,I/ActivityManager(  915): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3286 uid=10041 gids={50041}
,W/WeatherRequest( 1112): request cur loc, but there is no sys cur
,D/AccTypeManager( 3270): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  915): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3303 uid=10078 gids={50078}
,D/Process (  915): killProcessQuiet, pid=2814
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 2814:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/AccTypeManager( 3270): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3270): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/SMSBackup( 3303): Got a database change event
I/ActivityManager(  915): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3315 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/Process (  915): killProcessQuiet, pid=2884
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 2884:com.google.android.talk/u0a111 (adj 15): empty #17
,E/ExternalAccountType( 3270): Unsupported attribute readOnly
,D/AccTypeManager( 3270): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3270): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3270): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/CalendarApplication( 3315): onCreate
D/ProviderChangeReceiver( 3315): ---------------------------------------------------
,D/ProviderChangeReceiver( 3315): ProviderChangeReceiver onReceive, start to update notification!
,E/ExternalAccountType( 3270): Unsupported attribute readOnly
,D/AlertService( 3315): start to updateAlertNotification!
W/ContextImpl( 2970): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  915): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3330 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  915): Recipient 2814
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 3315): No fired or scheduled alerts
,D/HtcAlertUtils( 3315): -- cancelReminderNotification --
,D/HtcAlertUtils( 3315): broadcastExistReminder!
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  915): killProcessQuiet, pid=2913
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 2913:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 2913
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 2884
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3330): can't get weather sync account
I/ActivityManager(  915): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3345 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 3330): request cur loc, but there is no sys cur
,W/Settings( 3330): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3345): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3345): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  915): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3345): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,D/AppWidgetHostView( 1257): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1257): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  915): Resuming delayed broadcast
,I/RemoteViews.Performance( 1257): com.htc.widget.weatherclock 1 10 17
,D/Process (  915): killProcessQuiet, pid=2932
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3359 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  915): Killing 2932:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 2932
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(42819728): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3359 10071 null
,I/SensorManager(  915): mEventCount = 300
,D/TodoTaskshortcut( 3359): update TASK shortcut>
D/PMS     (  915): acquireWL(424582d0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3359 10071 null
D/PMS     (  915): releaseWL(42819728): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  915): Delay finish: com.htc.task/.TodoReceiver
,I/TodoTaskNotifyService( 3359): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  915): releaseWL(424582d0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3359): stopSelfResult true
I/ActivityManager(  915): Resuming delayed broadcast
,D/Process (  915): killProcessQuiet, pid=2953
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3374 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  915): Killing 2953:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 2953
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): releaseWL(425e34d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  915): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3386 uid=10082 gids={50082, 3003, 5012}
,D/Process (  915): killProcessQuiet, pid=2992
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  915): Killing 2992:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/SMSBackup( 3303): Got a database change event
,I/ActivityManager(  915): Recipient 2992
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3398 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  915): killProcessQuiet, pid=3049
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 3049:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 3049
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3398): create image Cache, size: 31457280.
I/ImageRamCache( 3398): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3398): create image Cache, size: 12582912.
,I/FeedSettings( 3398): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3398): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3398): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3398): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3398): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3398): loadGridSize() with Alternative
,I/ActivityManager(  915): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3413 uid=10091 gids={50091, 3003, 5012}
,D/CustomHighlightReceiver( 3398): [custom highlight] onReceive
V/AlarmManager(  915): sending alarm PendingIntent{42429df0: PendingIntentRecord{425ad3c8 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53577, Int=0
,D/CustomHighlightService( 3398): [custom highlight] onHandleIntent
,D/NewsDB  ( 3398): set custom highlight []
I/ActivityManager(  915): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3398): [custom highlight] set tags 
,D/MessagingShortcutReceiver( 2590): keep hiding shortcut bubble
D/MessagingShortcut( 2590): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2590): After query: 0
D/MessagingShortcut( 2590): mPresentUnreadCount: -1
,D/MessagingShortcut( 2590): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2590): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,I/ActivityManager(  915): Resuming delayed broadcast
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderNotification, total:0
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3359): update TASK shortcut>
,I/ActivityManager(  915): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3429 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  915): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1227): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  915): killProcessQuiet, pid=3069
I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Killing 3069:com.android.smith/u0a163 (adj 15): empty #17
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/CustomHighlightReceiver( 3398): [custom highlight] onReceive
D/CustomHighlightService( 3398): [custom highlight] onHandleIntent
,D/NewsDB  ( 3398): set custom highlight []
I/ActivityManager(  915): Recipient 3069
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/MessagingNotification( 2590): New incoming message, can't cancel notification now
,D/MessagingNotification( 2590): newMsgCnt: 0, false
,D/CustomHighlightService( 3398): [custom highlight] set tags 
I/ActivityManager(  915): Resuming delayed broadcast
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1996, uid=10029, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1996, uid=10029, userID:0
,D/WearableService( 1206): callingUid 10029, callindPid: 1206
,E/MDM     ( 1206): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1996, uid=10029, userID:0
,D/LocationInitializer( 1996): Restart initialization of location
I/ActivityManager(  915): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/MdScBoot( 3413): [8f0.1.] 30@-091154 -> 40@-091224
,D/MdScBoot( 3413): [8f0.2.] 40@-091224
W/GCoreFlp( 1206): No location to return for getLastLocation()
,D/Process (  915): killProcessQuiet, pid=3088
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/PMS     (  915): acquireWL(425e7768): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1206 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Killing 3088:com.google.android.youtube/u0a168 (adj 15): empty #17
,W/FusedLocationProvider( 1339): location=null
,D/Process (  915): killProcessQuiet, pid=3181
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  915): releaseWL(425e7768): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  915): Killing 3181:com.android.vending/u0a74 (adj 15): empty #17
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024025
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024031
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028885
,I/ActivityManager(  915): Resuming delayed broadcast
,D/GCM     ( 1339): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1339/10029)
,D/AuthorizationBluetoothService( 1339): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1339): Proximity feature is not enabled.
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  915): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1996): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/CustomHighlightReceiver( 3398): [custom highlight] onReceive
I/ActivityManager(  915): Resuming delayed broadcast
D/CustomHighlightService( 3398): [custom highlight] onHandleIntent
,D/NewsDB  ( 3398): set custom highlight []
I/ActivityManager(  915): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3398): [custom highlight] set tags 
I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Recipient 3181
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  915): Client com.google.android.youtube (pid 3088): Died!
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3088
,D/PMS     (  915): acquireWL(428096d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1339/10029)
,E/MDM     ( 1206): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1996, uid=10029, userID:0
D/PMS     (  915): releaseWL(428096d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1996, uid=10029, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1996, uid=10029, userID:0
,I/ActivityManager(  915): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/LocationInitializer( 1996): Restart initialization of location
,W/GCoreFlp( 1206): No location to return for getLastLocation()
,W/FusedLocationProvider( 1339): location=null
D/PMS     (  915): acquireWL(424fa590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1206 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(424fa590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024025
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028885
I/ActivityManager(  915): Resuming delayed broadcast
,D/GCM     ( 1339): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1339): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1339/10029)
,E/AuthorizationBluetoothService( 1339): Proximity feature is not enabled.
,V/GLSActivity( 1339): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  915): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  915): Resuming delayed broadcast
I/ActivityManager(  915): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1996): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  915): Resuming delayed broadcast
D/PMS     (  915): acquireWL(4259e448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1339/10029)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024025
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028885
D/PMS     (  915): releaseWL(4259e448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(426d2480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1339 10029 WorkSource{10029 com.google.android.gms}
,D/MtpReceiver( 2071): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2071): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2071): [MTP][handleMessage][startService]
,D/MtpReceiver( 2071): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2071): [MTP][handleMessage]-
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1339/10029)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023786
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023915
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024025
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024031
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028885
,D/MtpService( 2071): [MTP] startForeground
,I/RemoteViews( 1112): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1112): com.android.providers.media 0 1 10
I/ActivityManager(  915): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3457 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/PMS     (  915): releaseWL(426d2480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/MtpService( 2071): updating state; isCurrentUser=true, mMtpLocked=false
I/RemoteViews( 1112): com.android.providers.media (false,0)
D/MtpDatabase( 2071): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews.Performance( 1112): com.android.providers.media 2 1 15
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/MtpService( 2071): [isMtpConnected] connected: true
D/PMS     (  915): acquireWL(42942b20): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1996 10029 null
,D/Process (  915): killProcessQuiet, pid=3005
,I/ActivityManager(  915): Killing 3005:com.android.settings/1000 (adj 15): empty #17
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  915): Recipient 3005
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3457): Loading default preferences
,I/iu.UploadsManager( 1996): End new media; added: 0, uploading: 0, time: 179 ms
D/PMS     (  915): releaseWL(42942b20): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,W/Resources( 3457): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  915): New client listening to asynchronous messages
,D/SyncApplication( 3457): Overriding preferences with custom values
,D/SyncApplication( 3457): Updating preferences succeeded
,E/SyncApplication( 3457): Application created.
D/VolumeInfo( 3457): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3457): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3457): Found 0 mount point(s)
,V/VolumeInfo( 3457): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3457): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3457): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3457): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3457): getNewCalendarAuthority()...
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3457, uid=10008, userID:0
,D/SyncApplication( 3457): enableAppOperation()+
,D/SyncApplication( 3457): enableAppOperation()-
,D/HTCUtilities( 3457): isNeorSinged() + 
W/PackageManager(  915): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3457, uid=10008, userID:0
W/PackageManager(  915): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3457): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3457): isNeorSinged() return false
D/CDMountReceiver( 3457): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3457): USB connected to PC
,D/FOTAReceiver( 3457): onReceive() enter 
,D/FOTAReceiver( 3457): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  915): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3477 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  915): killProcessQuiet, pid=3219,
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 3219:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 3219
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3477): -onCreate()
,V/Settings:HtcSettingsApplication( 3477): [3477/3477] onCreate()
,D/TetherSettings( 3477): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3477): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3477): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3477): Cust_ConnectToPC   : spcsc>false
D/        ( 3477): Cust_ConnectToPC   : IPT>true
,D/        ( 3477): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3477): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3477): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3477): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3477): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3477): Cust_ConnectToPC   : spcsc>false
D/        ( 3477): Cust_ConnectToPC   : IPT>true
D/        ( 3477): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3477): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3477): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3477): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3477): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3477): usb_cable_connect = 1
,D/SmartNS_Utility( 3477): usb_denied = 0
I/SmartNS_NSReceiver( 3477): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3477): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3477): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3477): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3477): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3477):  defaultType:0
,I/SmartNS_PSService( 3477): fail notificaiton:false
,D/SmartNS_Utility( 3477): usb_cable_connect = 1
W/ContextImpl( 3477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3477): usb_denied = 0
,I/SmartNS_PSService( 3477): usb notificaiton:true
,V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  915): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  915): bSetPropertyMultiRAB:false
I/ActivityManager(  915): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  915): getActiveNetworkInfo called by com.android.settings (3477/1000)
,I/RemoteViews( 1112): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1112): com.android.settings 2 1 10
,D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3477): usb_cable_connect = 1
D/SmartNS_Utility( 3477): usb_denied = 0
,I/SmartNS_PSService( 3477): usb notificaiton:true
,V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  915): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  915): bSetPropertyMultiRAB:false
I/ActivityManager(  915): Resuming delayed broadcast
D/ConnectivityService(  915): getActiveNetworkInfo called by com.android.settings (3477/1000)
,I/ActivityManager(  915): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
W/WeatherUtility( 3330): can't get weather sync account
D/SmartNS_Utility( 3477): usb_cable_connect = 1
D/SmartNS_Utility( 3477): usb_denied = 0
I/RemoteViews( 1112): com.android.settings (true,33751552)
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews.Performance( 1112): com.android.settings 3 1 10
I/SmartNS_PSService( 3477): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3477): USB Plugged, Set USBPlugged=  truePSenabled:false
W/WeatherRequest( 3330): request cur loc, but there is no sys cur
,W/Settings( 3330): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  915): Resuming delayed broadcast
,D/AppWidgetHostView( 1257): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1257): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1257): com.htc.widget.weatherclock 1 7 17
,D/AppWidgetHostView( 1257): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1257): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1257): com.google.android.googlequicksearchbox 1 0 5
,I/ActivityManager(  915): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3494 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 3494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  915): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageService( 3494): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3494): MY_DEBUG = false
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,I/dalvikvm-heap(  915): Grow heap (frag case) to 17.507MB for 143264-byte allocation
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,I/ActivityManager(  915): Resuming delayed broadcast
,D/PMS     (  915): acquireWL(42857158): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3494 1000 null
,D/Process (  915): killProcessQuiet, pid=3258
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  915): Killing 3258:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/WeatherUtility( 1112): can't get weather sync account
,D/WeatherUtility( 1296): Weather sync is On
,D/WSP     ( 1296): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 3258
,W/WeatherUtility( 3330): can't get weather sync account
I/ActivityManager(  915): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3511 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherRequest( 3330): request cur loc, but there is no sys cur
,W/Settings( 3330): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,D/AppWidgetHostView( 1257): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1257): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1257): com.htc.widget.weatherclock 2 10 17
,I/ActivityManager(  915): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/HtcModeClient( 1492): handler message = 4011
,E/HtcModeClient( 1492): Check connection and retry 5 times.
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3529 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  915): killProcessQuiet, pid=3270
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3270:com.htc.contacts/u0a44 (adj 15): empty #17
,D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  915): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  915): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  915): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  915): Settings:Agentvalue: 0
W/Settings:Agent(  915): >> traceCallingStack()
W/Settings:Agent(  915): Process.myPid(): 915
W/Settings:Agent(  915): Process.myTid(): 1241
,W/Settings:Agent(  915): Process.myUid(): 1000
,W/Settings:Agent(  915): 
W/Settings:Agent(  915): 
,W/System.err(  915): java.lang.Throwable: stack dump
,W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  915): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  915): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  915): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  915): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  915): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  915): 
,W/Settings:Agent(  915): << traceCallingStack(): 7(ms)
,D/BluetoothManagerService(  915): Message: MESSAGE_DISABLE
,D/WifiManager( 3019): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
W/HtcDLNAServiceManager(  915): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  915): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  915): Settings:Agentvalue: 0
D/WifiService(  915): New client listening to asynchronous messages
D/WifiService(  915): setWifiEnabled: false pid=3019, uid=10396
E/WifiService(  915): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  915): isSprintWifiRestricted(): false
I/WifiService(  915): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  915): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,W/Settings:Agent(  915): >> traceCallingStack()
W/Settings:Agent(  915): Process.myPid(): 915
W/Settings:Agent(  915): Process.myTid(): 1367
W/Settings:Agent(  915): Process.myUid(): 1000
W/Settings:Agent(  915): 
W/Settings:Agent(  915): 
,W/System.err(  915): java.lang.Throwable: stack dump
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  915): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  915): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  915): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  915): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  915): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  915): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  915): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  915): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
,W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  915): 
,W/Settings:Agent(  915): << traceCallingStack(): 3(ms)
I/jxcore-log( 3019): ****TEST TOOK:  5048  ms ****
I/jxcore-log( 3019): 
,I/jxcore-log( 3019): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3019): 
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 3270
,V/AlarmManager(  915): sending alarm PendingIntent{42176550: PendingIntentRecord{425b4658 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1447834347649, Int=0
,D/Process (  915): killProcessQuiet, pid=3315
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3315:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3315
,I/MusicStore( 3529): Database version: 95
,W/ContextImpl( 3529): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3529): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3529): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils-trace( 3542): Error opening trace file: No such file or directory (2)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3529): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3529): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3529, uid=10154, userID:0
,D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
,D/MediaRouterService(  915): Client com.google.android.music (pid 3529): Registered
,I/MediaRouter( 3529): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
,D/DFPI.PIReciver( 3345): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3345): onHandleIntent
,I/DFPI.ApkInstallService( 3345): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3345): check CID = HTC__032
,I/DFPI.ApkInstallService( 3345): There is no Demo.apk in sd card or phone storage
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.music (3529/10154)
I/ActivityManager(  915): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/MediaRouter( 3529): getSelectedRoute
I/ActivityManager(  915): Resuming delayed broadcast
I/ActivityManager(  915): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3529, uid=10154, userID:0
,D/PMS     (  915): acquireWL(4209fa48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,I/ActivityManager(  915): Resuming delayed broadcast
,D/PMS     (  915): releaseWL(4209fa48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  915): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3561 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  915): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.musicenhancer (3561/10053)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3561): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,D/CustomizationManager( 3542): ====startRecUseTime====
,D/htc.customization.log.level( 3542):  is 
,W/CustomizationLogLevel( 3542): Level value is invalid, use default level 2
,D/CustomizationManager( 3542):  Read ACC file spent 0.062 (s)
,D/CIDMapFileReader( 3542): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3542): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3542): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3542): Parsing tag item name = HTC__A07
,D/CIDMapFileReader( 3542): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3542): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3542): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3542): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3542): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3542): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3542): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3542): Parsing tag category name = system
,I/CustomizationCIDLoader( 3542): Parsing tag category name = application
,I/CustomizationCIDLoader( 3542): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3542): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3542): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3542): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3542): Parsing tag category name = Settings
D/CustomizationManager( 3542):  Read CID file spent 0.110 (s)
,D/CustomizationManager( 3542):  All configurations done spent 0.110 (s)
W/HtcNativeFlag( 3542): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3542): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3542): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3542): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  915): deletePackageAsUser: pkg=com.example.hello, pid=3542, uid=2000 user=0
,I/ActivityManager(  915): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  915): killProcessQuiet, pid=3019
,W/asset   (  915): Copying FileAsset 0x6b782190 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  915): Killing 3019:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  915): Force removing ActivityRecord{423f7a30 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  915): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  915): Skipping PackageSetting{422ae370 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  915): Force stopping com.example.hello appid=10396 user=0: pkg removed
,W/InputDispatcher(  915): channel '4268d980 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  915): channel '4268d980 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  915): Client connection lost with reason: 4
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/Prism.ItemManager( 3398): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3398): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/InputDispatcher(  915): Attempted to unregister already unregistered input channel '4268d980 com.example.hello.MainActivity (s)'
,W/SystemReader( 1242): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1324): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1206): Ignoring removeGeofence because network location is disabled.
I/FeedHostManager( 1257): [onResume]
,I/FeedProviderManager( 1257): onResume
I/WindowManager(  915): WINDOW DIED Window{4268d980 u0 com.example.hello/com.example.hello.MainActivity}
D/PMS     (  915): acquireWL(42914168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1206 10029 WorkSource{10029 com.google.android.gms}
W/WindowManager(  915): Failed looking up window
W/WindowManager(  915): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4292fa48 does not exist
W/WindowManager(  915): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  915): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  915): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  915): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  915): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  915): WIN DEATH: null
I/SocialFeedProvider( 1257): +onResume
I/SocialFeedProvider( 1257): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1257): -onResume
,I/ConnectivityHelper( 1257): [getCurrentConnectionType] no network connection
D/PMS     (  915): releaseWL(42914168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.launcher (1257/10076)
,I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1257): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1324): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1324): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
I/PackageManager(  915):   Scheme: "smsto"
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
,E/ExternalAccountType( 1324): Unsupported attribute readOnly
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1227 :
,D/PhoneApp( 1227): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/InputMethodManagerService(  915): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  915): Got RemoteException sending setActive(false) notification to pid 3019 uid 10396
,W/Binder  ( 1191): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1191): java.lang.NullPointerException
W/Binder  ( 1191): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1191): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1191): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1191): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  915): Enable input method client, pid=1257
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460,
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	,at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213),
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26),
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460,
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
I/SocialFeedProvider( 1257): +disConnect socialManager
,I/SocialFeedProvider( 1257): disconnect socialManager
,I/SocialFeedProvider( 1257): -disConnect socialManager
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
W/PackageManager(  915): Unable to load service info ResolveInfo{4276c398 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  915): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  915): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  915): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  915): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  915): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  915): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  915): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  915): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  915): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  915): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  915): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3494): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
E/SQLiteDatabase( 3494): Error inserting ...
E/SQLiteDatabase( 3494): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3494): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3494): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3494): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3494): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3494): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3494): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3494): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3494): (3850) statement aborts at 34: [SELECT * FROM smartsync_golden_wed ORDER BY date] disk I/O error
E/SQLiteDBG( 3494): func: nativeExecuteForCursorWindow errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5c9a0460
,E/SQLiteQuery( 3494): exception: disk I/O error (code 3850); query: SELECT * FROM smartsync_golden_wed ORDER BY date
D/PMS     (  915): releaseWL(42857158): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  915): Resuming delayed broadcast
,D/Process (  915): killProcessQuiet, pid=2970
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3586 uid=10081 gids={50081, 5001, 1028, 1015}
I/ActivityManager(  915): Killing 2970:com.android.settings:remote/1000 (adj 15): empty #17
,I/SoundPicker( 3586): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3586): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3586): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3586): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3586): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3586): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  915): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3586): MODE_GSM access default DB
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3586): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3586): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3586): MODE_GSM access default DB
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3586): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,W/AtomicFile(  915): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager(  915): Recipient 2970
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  915): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  915): start
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
W/AppWidgetServiceImpl(  915): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3586): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3586): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3586): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  915): Resuming delayed broadcast
D/DFPI.PIReciver( 3345): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3345): onHandleIntent
I/DFPI.ApkInstallService( 3345): Media Scan Finished Case 
I/ActivityManager(  915): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3345): check CID = HTC__032
I/DFPI.ApkInstallService( 3345): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  915): sending alarm PendingIntent{42532698: PendingIntentRecord{424392d8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1447834349718, Int=0
,I/SocialManager[SocialBiLogHelper]( 3398): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3398): last commit ulog time 1447739810778
,I/SocialManager[SocialBiLogHelper]( 3398): do commit ulog
,E/SharedPreferencesImpl( 3398): Couldn't rename file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml to backup file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml.bak
,E/SharedPreferencesImpl( 3398): Couldn't rename file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml to backup file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml.bak
,E/SharedPreferencesImpl( 3398): Couldn't rename file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml to backup file /data/data/com.htc.launcher/shared_prefs/NewsPreference_value.xml.bak
,I/ActivityManager(  915): Delaying start of: ServiceRecord{4273bb70 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,V/SocialManagerService( 1296): getDataSources
,I/SocialManagerService( 1296): plugin added: com.facebook.auth.login
,I/SocialManagerService( 1296): plugin added: com.twitter.android.auth.login
,I/SocialManagerService( 1296): plugin added: com.htc.linkedin
,I/SocialManagerService( 1296): plugin added: com.htc.venuesrecommend
,I/SocialManagerService( 1296): plugin added: com.htc.sense.socialnetwork.instagram
,I/SocialManagerService( 1296): plugin added: com.htc.drive.activator
,I/SocialManagerService( 1296): plugin added: com.htc.socialnetwork.rss.octopus
,I/SocialManagerService( 1296): plugin added: com.htc.opensense.htcnews
,I/SocialManagerService( 1296): plugin added: com.google
,I/SocialManagerService( 1296): device total memory: 1873M
,I/SocialManagerService( 1296): groupAccounts

```
