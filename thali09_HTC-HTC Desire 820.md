#### Test 50388019c82294c_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/QXDM2SD:HtcNative( 1216): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
D/Process (  902): killProcessQuiet, pid=2535
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  902): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2838 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  902): Killing 2535:com.htc.reportagent/u0a66 (adj 15): empty #17
I/ActivityManager(  902): Recipient 2535
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/Settings:HtcSettingsApplication( 2838): [2838/2838] onCreate()
W/ContextImpl( 2838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  902): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/HtcCupdXmlParser( 2807): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  902): Resuming delayed broadcast
D/Process (  902): killProcessQuiet, pid=2552
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2853 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  902): Killing 2552:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/AlarmManager(  902): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  902): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  902): [AlarmQueuing] init alarm queuing list
I/ActivityManager(  902): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2865 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  902): Recipient 2552
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  902): killProcessQuiet, pid=2564
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 2564:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  902): Recipient 2564
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcFingerPrintQuickLaunchProvider( 2853): -onCreate()
V/Settings:HtcSettingsApplication( 2853): [2853/2853] onCreate()
W/ContextImpl( 2853): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  902): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@427a97c8
D/TetherSettings( 2853): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2853): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2853): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2853): Cust_ConnectToPC   : spcsc>false
D/        ( 2853): Cust_ConnectToPC   : IPT>true
D/        ( 2853): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2853): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 2853): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2853): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2853): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2853): Cust_ConnectToPC   : spcsc>false
D/        ( 2853): Cust_ConnectToPC   : IPT>true
D/        ( 2853): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2853): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2853): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2853): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2853): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 2853): setISNotification
I/AlarmManager(  902): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@427ab578
D/SmartNS_Utility( 2853): usb_cable_connect = 1
D/SmartNS_Utility( 2853): usb_denied = 0
I/SmartNS_PSService( 2853): usb notificaiton:true
V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  902): bSetPropertyMultiRAB:false
D/Process (  902): killProcessQuiet, pid=2579
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/AlarmManager(  902): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@427ac5d8
D/ConnectivityService(  902): getActiveNetworkInfo called by com.android.settings (2853/1000)
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  902): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  902): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  902): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  902): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  902): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  902): Killing 2579:com.htc.updater/u0a85 (adj 15): empty #17
D/SmartNS_Utility( 2853): usb_cable_connect = 1
D/SmartNS_Utility( 2853): usb_denied = 0
I/SmartNS_PSService( 2853): usb notificaiton:true
V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  902): bSetPropertyMultiRAB:false
D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  902): getActiveNetworkInfo called by com.android.settings (2853/1000)
I/ActivityManager(  902): Recipient 2579
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  902): killProcessQuiet, pid=2609
I/ActivityManager(  902): Killing 2609:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/RemoteViews( 1105): com.android.settings (true,33751552)
W/ContextImpl(  902): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  902): Recipient 2609
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/OnDemandProgressBar( 1105): release indeterminate drawable android.widget.OnDemandProgressBar{41bb01b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1105): com.android.settings 4 18 0 10
I/ActivityManager(  902): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2882 uid=9987 gids={49987}
I/RemoteViews( 1105): com.android.settings (true,33751552)
I/SensorManager(  902): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@424bf5b8, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
I/RemoteViews.Performance( 1105): com.android.settings 1 1 10
W/SensorService(  902): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 2
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424bf5b8, eanble = 1, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4230f100
W/SensorService(  902): Listener[1] = com.android.server.power.DisplayPowerController$10@42266998
W/SensorService(  902): Listener[2] = com.htc.smartdim.sensor_eye@424bf5b8
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  902): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@424bf5b8, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  902): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  902): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  902): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{427c0170 u0 ReceiverList{427c0110 902 system/1000/u0 local:427bfe90}}
D/NfcUiccLockService( 2882): -- To check whether previous opened channel needed to be closed ...
D/Process (  902): killProcessQuiet, pid=2638
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2896 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  902): Killing 2638:com.htc.android.worldclock/u0a90 (adj 15): empty #17
W/SensorService(  902): pid=902, uid=1000
W/SensorService(  902): Active sensors: size = 3
W/SensorService(  902): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  902): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  902): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  902): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424bf5b8, eanble = 1, strlen(mName) = 36
W/SensorService(  902): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  902): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4230f100
W/SensorService(  902): Listener[1] = com.android.server.power.DisplayPowerController$10@42266998
W/SensorService(  902): Listener[2] = com.htc.smartdim.sensor_eye@424bf5b8
W/SensorService(  902): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/Process (  902): killProcessQuiet, pid=2658
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2908 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  902): Killing 2658:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  902): Recipient 2658
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 2638
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/cutils-trace( 2876): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 2876): ====startRecUseTime====
D/htc.customization.log.level( 2876):  is 
W/CustomizationLogLevel( 2876): Level value is invalid, use default level 2
E/YouTube ( 2908): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 2908): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 2908): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 2908): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/CustomizationManager( 2876):  Read ACC file spent 0.069 (s)
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2876): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2876): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2876): Parsing tag category name = system
I/CustomizationCIDLoader( 2876): Parsing tag category name = application
I/CustomizationCIDLoader( 2876): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2876): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2876): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2876): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2876): Parsing tag category name = Settings
D/CustomizationManager( 2876):  Read CID file spent 0.115 (s)
D/CustomizationManager( 2876):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 2876): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2876): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2876): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2876): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  902): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  902): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  902): <<acquire mCpuPerf_Freq wakelock
W/asset   (  902): Copying FileAsset 0x62b23eb8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  902): @test_code: getHtcIntentFlag: 0 obj: 1115466656
I/ActivityManager(  902): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2876
D/PMS     (  902): acquireHCC(427cb0e8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 902 1000 null
D/PMS     (  902): acquireHCC(427cbd28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 902 1000 null
I/FeedHostManager( 1244): [onPause]
I/FeedProviderManager( 1244): onPause
I/FeedHostManager( 1244): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420cc270
I/SocialFeedProvider( 1244): +onPause
I/SocialFeedProvider( 1244): -onPause
D/PMS     (  902): acquireWL(427cd318): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 902 1000 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.youtube (2908/10168)
I/ActivityManager(  902): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2944 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1244): [trimMemory] 20
W/asset   ( 2944): Copying FileAsset 0x5c845428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 2908): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
V/WebViewChromiumFactoryProvider( 2944): Binding Chromium to main looper Looper (main, tid 1) {41b91400}
I/LibraryLoader( 2944): Expected native library version number "",actual native library version number ""
I/chromium( 2944): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2944): Initializing chromium process, renderers=0
W/System.err(  902): java.lang.Throwable: stack dump
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  902): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  902): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  902): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425e03c0:true
D/BluetoothAdapter( 2944): 1102736888: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  902): acquireWL(4298d9f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): acquireWL(4283bdb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  902): releaseWL(4298d9f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/YouTube ( 2908): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
I/Adreno-EGL( 2944): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2944): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2944): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2944): Local Branch: 
I/Adreno-EGL( 2944): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2944): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2944):                  aa63bbd948f41d15fc72f585e
D/YouTube ( 2908): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,W/chromium( 2944): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 2944): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 2944): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 2944): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2944): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 2944): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 2944): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2944): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 2944): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2944): CordovaWebView is running on device made by: HTC
,D/YouTube ( 2908): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,I/GAV2    ( 2593): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1956): Google Analytics 8.3.01 is starting up.
,D/YouTube ( 2908): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
,D/MediaRouterService(  902): Client com.google.android.youtube (pid 2908): Registered
,I/MediaRouter( 2908): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
,D/YouTube ( 2908): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 2908): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1447782148&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,W/AwContents( 2944): nativeOnDraw failed; clearing to background color.
D/ConnectivityService(  902): getNetworkInfo networkType=0 called by com.google.android.youtube (2908/10168)
D/libc    ( 2908): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 2908): [NET] getaddrinfo-,err=8
D/libc    ( 2908): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2908): [NET] getaddrinfo-, 1
D/libc    ( 2908): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: ,
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2908): [NET] getaddrinfo_proxy-
,E/GoogleConversionPing( 2908): Error sending ping
,I/InputMethodManagerService(  902): Disable input method client, pid=1244
,W/ResourceType( 2944): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 2944): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bd8140, mServedView=org.apache.cordova.engine.SystemWebView{41b9e118 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  902): Enable input method client, pid=2944
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/AwContents( 2944): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2908): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2908): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,I/ActivityManager(  902): Displayed com.example.hello/.MainActivity: +373ms
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,D/MediaRouter( 2908): getSelectedRoute
,D/YouTube ( 2908): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/PMS     (  902): releaseWL(427cd318): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.youtube (2908/10168)
,I/ActivityManager(  902): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  902): Resuming delayed broadcast
,D/YouTube ( 2908): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,I/chromium( 2944): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2944): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 2944): Set native->JS mode to OnlineEventsBridgeMode
,D/YouTube ( 2908): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2908): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2908): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1956): Spent 30ms computing apk sha1.
,D/FileApkUtils( 1956): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1956): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/jxcore_app_log( 2944): JniHelper::setJavaVM(0x4174a010), pthread_self() = 1657654760
D/JX-Cordova( 2944): jxcore cordova android initializing
,D/FileApkUtils( 1956): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,I/ActivityManager(  902): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/GmsModuleFndr( 1956): Beginning GMS chimera module scan
,E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,W/asset   ( 1956): Copying FileAsset 0x64eda890 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
D/PMS     (  902): acquireWL(4273c2b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,W/jxcore-log( 2944): Initializing JXcore engine
,W/jxcore-log( 2944): JXcore engine is ready
E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1956): Beginning module configuration check
W/jxcore-log( 2944): Starting JXcore engine
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1956): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
W/dalvikvm( 1956): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1956): Module APKs unchanged, check complete
,D/PMS     (  902): acquireWL(4273c208): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  902): acquireWL(4273b430): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1956): COMPAT: Multi user not supported
,D/PMS     (  902): releaseWL(4273c2b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1326): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1326/10029)
I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1447758960449 min interval config: 0 actual interval: 23188180
I/GCoreUlr( 1956): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1194): DispatchingService.onCreate()
,I/CheckinService( 1956): Disabling old GoogleServicesFramework version
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/SystemUpdateService( 1956): onCreate
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,D/SystemUpdateService( 1956): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  902): acquireWL(41fc51e8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1956, uid=10029, userID:0
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1956, uid=10029, userID:0
V/AuthZen ( 1956): Handling intent: android.intent.action.BOOT_COMPLETED
,D/PMS     (  902): acquireWL(41f2fcc8): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
I/CheckinService( 1956): Checking schedule, now: 1447782148705 next: 1447758990383
,I/CheckinService( 1956): active receiver: enabled
I/SystemUpdateService( 1956): cancelUpdate (empty URL)
,I/SystemUpdateService( 1956): active receiver: disabled
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,D/AuthZenEventHandler( 1956): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,D/PMS     (  902): releaseWL(41f2fcc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/GCoreUlr( 1194): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  902): releaseWL(4273b430): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  902): releaseWL(4273c208): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
D/SystemUpdateService( 1956): onDestroy
,W/jxcore-log( 2944): Platform android
W/jxcore-log( 2944): 
,W/jxcore-log( 2944): Process ARCH arm
W/jxcore-log( 2944): 
,W/BaseAppContext( 1956): Using Auth Proxy for data requests.
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1194, uid=10029, userID:0
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/jxcore-log( 2944): JXcore Cordova bridge is ready!
I/jxcore-log( 2944): 
,W/jxcore-log( 2944): JXcore engine is started
,I/AuthZen ( 1956): Fetching signing key...
,I/AuthZen ( 1956): Signing key fetched successfully!
,W/BaseAppContext( 1956): Using Auth Proxy for data requests.
,E/jxcore-log( 2944): >> HTC-HTC Desire 820
E/jxcore-log( 2944): 
,I/jxcore-log( 2944): Total memory 1964650496
I/jxcore-log( 2944): 
I/jxcore-log( 2944): Free memory 707186688
I/jxcore-log( 2944): 
I/jxcore-log( 2944): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): process.cwd /data/data/com.example.hello/files/www/jxcore,
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): userPath [ 'www' ]
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): Size 720 1184
I/jxcore-log( 2944): 
,I/jxcore-log( 2944): Screen Brightness 142
I/jxcore-log( 2944): 
,E/jxcore-log( 2944): Dummy Error Log.
E/jxcore-log( 2944): 
D/AuthZenTransactionCache( 1956): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1956): Clearing transaction cache
,I/GCoreUlr( 1194): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1194): Unbound from all location providers
D/PMS     (  902): acquireWL(427f71e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(427f71e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(41fc51e8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/ActivityManager(  902): Resuming delayed broadcast
,I/GCoreUlr( 1194): DispatchingService.onDestroy()
,I/GCoreUlr( 1194): Stopping handler for UlrDispSvcFast
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
D/PMS     (  902): acquireWL(427fda90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  902): releaseWL(427fda90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1194): Unbound from all location providers
,D/PMS     (  902): acquireWL(427ff600): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1956 10029 null
,D/PMS     (  902): acquireWL(427ffef0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  902): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,W/dalvikvm( 1326): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/PMS     (  902): releaseWL(427ff600): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  902): releaseWL(427ffef0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  902): Resuming delayed broadcast
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  902): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  902): Resuming delayed broadcast
,W/Auth    ( 1326): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  902): acquireWL(428062d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1326 10029 null
I/ActivityManager(  902): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  902): releaseWL(428062d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,W/dalvikvm( 1326): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
I/ActivityManager(  902): Resuming delayed broadcast
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1326): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1326): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  902): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3051 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/PMS     (  902): acquireWL(4280d6b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 902 1000 null
D/PMS     (  902): releaseWL(4280d6b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3051, uid=10074, userID:0
,D/Finsky  ( 3051): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  902): getAllNetworkInfo called by com.android.vending (3051/10074)
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  902): getAllNetworkInfo called by com.android.vending (3051/10074)
,D/Finsky  ( 3051): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3051): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3051): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3051): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3051, uid=10074, userID:0
,D/Volley  ( 3051): [286] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3051): [279] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3051): Skipping gmscore version check
,D/Process (  902): killProcessQuiet, pid=2670
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 2670:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 2670
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3051): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3051): [1] 2.run: Finished loading 1 libraries.
,D/AutoSetting( 1294): receiver - intent: android.intent.action.USER_PRESENT
,D/Finsky  ( 3051): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/TetherSettings( 2853): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2853): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2853): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2853): Cust_ConnectToPC   : spcsc>false
D/        ( 2853): Cust_ConnectToPC   : IPT>true
D/        ( 2853): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2853): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 2853): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2853): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2853): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/ActivityManager(  902): Delay finish: com.android.settings/.NSReceiver
D/AutoSetting( 1294): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/jxcore-log( 2944): getBuffer is called!!!!
I/jxcore-log( 2944): 
,I/ActivityManager(  902): Resuming delayed broadcast
,I/PSReceiver( 2853): onReceive:android.intent.action.USER_PRESENT
,D/Finsky  ( 3051): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/SmartNS_PSService( 2853): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 2853): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2853):  defaultType:0
W/ContextImpl( 2853): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/HtcModeClient( 1480): handler message = 4011
,E/HtcModeClient( 1480): Check connection and retry 4 times.
,I/GAV2    ( 2700): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  902): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3092 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3092): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3092): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3092): Loading: swewebviewchromium
,I/LibraryLoader( 3092): Time to load native libraries: 29 ms (timestamps 9550-9579)
,I/LibraryLoader( 3092): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3092): Initializing chromium process, renderers=9
I/LibraryLoader( 3092): Expected native library version number "",actual native library version number ""
,I/chromium( 3092): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/CpuWake (  902): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  902): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  902): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  902): <<release mCpuPerf_Freq wakelock
,D/PMS     (  902): releaseHCC(427cb0e8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  902): releaseHCC(427cbd28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
W/chromium( 3092): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3092): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3092): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3092): Local Branch: 
I/Adreno-EGL( 3092): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3092): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3092):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  902): Killing 2472:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  902): killProcessQuiet, pid=2472
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1271): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1480): SIM state: ABSENT
I/SIMStateChangeReceiver( 1480): phoneType = 0
,I/SIMStateChangeReceiver( 1480): remove notification
I/ActivityManager(  902): Recipient 2472
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3131 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  902): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3143 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  902): killProcessQuiet, pid=2700
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 2700:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 2700
,W/SystemReader( 2487): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2487): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2487): onReceive()
D/ExchangePolicystatus( 2487): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2487): onReceive(): else
,D/Process (  902): killProcessQuiet, pid=2742
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1216): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  902): Killing 2742:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  902): Recipient 2742
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 1105): can't get weather sync account
I/ActivityManager(  902): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3159 uid=10041 gids={50041}
,W/WeatherRequest( 1105): request cur loc, but there is no sys cur
,D/AccTypeManager( 3143): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  902): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3175 uid=10078 gids={50078}
,D/Process (  902): killProcessQuiet, pid=2685
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 2685:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/AccTypeManager( 3143): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3143): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3175): Got a database change event
,E/ExternalAccountType( 3143): Unsupported attribute readOnly
,D/Process (  902): killProcessQuiet, pid=2763
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3187 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  902): Killing 2763:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3143): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3143): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3143): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/CalendarApplication( 3187): onCreate
D/ProviderChangeReceiver( 3187): ---------------------------------------------------
,D/ProviderChangeReceiver( 3187): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3187): start to updateAlertNotification!
,W/ContextImpl( 2838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,E/ExternalAccountType( 3143): Unsupported attribute readOnly
I/ActivityManager(  902): Recipient 2685
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3202 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/AlertService( 3187): No fired or scheduled alerts
,D/HtcAlertUtils( 3187): -- cancelReminderNotification --
,D/HtcAlertUtils( 3187): broadcastExistReminder!
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  902): killProcessQuiet, pid=2790
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 2790:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  902): Recipient 2763
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 2790
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3202): can't get weather sync account
I/ActivityManager(  902): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3217 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3217): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3217): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3217): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
W/WeatherRequest( 3202): request cur loc, but there is no sys cur
,W/Settings( 3202): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3231 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=2807
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 2807:com.htc.htccupd/u0a17 (adj 15): empty #17
,D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1244): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  902): Recipient 2807
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews.Performance( 1244): com.htc.widget.weatherclock 1 13 17
,D/PMS     (  902): acquireWL(42481520): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3231 10071 null
,D/PMS     (  902): acquireWL(4247c5e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3231 10071 null
,D/PMS     (  902): releaseWL(42481520): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  902): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3231): update TASK shortcut>
,I/TodoTaskNotifyService( 3231): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  902): releaseWL(4247c5e8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  902): Resuming delayed broadcast
,W/NotifyReceiver( 3231): stopSelfResult true
,D/Process (  902): killProcessQuiet, pid=2822
I/ActivityManager(  902): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3246 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  902): Killing 2822:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3258 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  902): Recipient 2822
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  902): killProcessQuiet, pid=2865
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 2865:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/SMSBackup( 3175): Got a database change event
I/ActivityManager(  902): Recipient 2865
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3270 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  902): killProcessQuiet, pid=2882
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.appDiedLocked:4131 
I/ActivityManager(  902): Killing 2882:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 2882
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3270): create image Cache, size: 31457280.
I/ImageRamCache( 3270): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3270): create image Cache, size: 12582912.
,I/FeedSettings( 3270): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3270): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3270): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3270): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3270): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3270): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3270): [custom highlight] onReceive
,D/CustomHighlightService( 3270): [custom highlight] onHandleIntent
,I/ActivityManager(  902): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3270): set custom highlight []
,D/CustomHighlightService( 3270): [custom highlight] set tags 
,D/MessagingShortcutReceiver( 2487): keep hiding shortcut bubble
D/MessagingShortcut( 2487): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2487): After query: 0
D/MessagingShortcut( 2487): mPresentUnreadCount: -1
,D/MessagingShortcut( 2487): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2487): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,I/ActivityManager(  902): Resuming delayed broadcast
D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1531): [EventService] reorderNotification, total:0
,D/DotMatrix( 1531): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1531): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3231): update TASK shortcut>
I/ActivityManager(  902): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1216): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  902): killProcessQuiet, pid=2896
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Killing 2896:com.android.smith/u0a163 (adj 15): empty #17
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  902): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3286 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  902): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360022497
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023013
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023132
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023138
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023143
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360027424
D/MessagingNotification( 2487): New incoming message, can't cancel notification now
D/MessagingNotification( 2487): newMsgCnt: 0, false
V/AlarmManager(  902): sending alarm PendingIntent{420f9a80: PendingIntentRecord{4267da58 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20177, Int=1800000
I/ActivityManager(  902): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3300 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  902): sending alarm PendingIntent{4246f950: PendingIntentRecord{424647a8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=46186, Int=259200000
V/AlarmManager(  902): sending alarm PendingIntent{41e3db98: PendingIntentRecord{42547218 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49326, Int=0
V/AlarmManager(  902): sending alarm PendingIntent{425fd340: PendingIntentRecord{426072c8 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1447758000000, Int=86400000
I/ActivityManager(  902): Recipient 2896
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MdScBoot( 3286): [8a8.1.] 30@-184203 -> 40@-184230
I/ActivityManager(  902): Resuming delayed broadcast
D/Process (  902): killProcessQuiet, pid=2908
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  902): killProcessQuiet, pid=3051
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 2908:com.google.android.youtube/u0a168 (adj 15): empty #17
D/PMS     (  902): releaseWL(4283bdb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  902): Killing 3051:com.android.vending/u0a74 (adj 15): empty #17
I/ActivityManager(  902): Recipient 3051
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WearableService( 1194): callingUid 10029, callindPid: 1194
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
E/MDM     ( 1194): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1956): Restart initialization of location
I/ActivityManager(  902): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
W/GCoreFlp( 1194): No location to return for getLastLocation()
W/FusedLocationProvider( 1326): location=null
D/PMS     (  902): acquireWL(4263d4e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  902): Recipient 2908
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  902): Client com.google.android.youtube (pid 2908): Died!
D/PMS     (  902): releaseWL(4263d4e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360022497
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023013
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023132
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023138
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023143
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360027424
I/ActivityManager(  902): Resuming delayed broadcast
D/GCM     ( 1326): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1326): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1326): Proximity feature is not enabled.
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1326/10029)
V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  902): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  902): Resuming delayed broadcast
V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/PMS     (  902): acquireWL(4262c4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1326 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1326/10029)
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  902): releaseWL(4262c4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/MDM     ( 1194): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
D/LocationInitializer( 1956): Restart initialization of location
I/ActivityManager(  902): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
W/GCoreFlp( 1194): No location to return for getLastLocation()
W/FusedLocationProvider( 1326): location=null
D/PMS     (  902): acquireWL(42452f98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): releaseWL(42452f98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360022497
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023013
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023132
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023138
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023143
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360027424
I/ActivityManager(  902): Resuming delayed broadcast
D/GCM     ( 1326): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1326): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1326): Proximity feature is not enabled.
V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1326/10029)
I/ActivityManager(  902): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  902): Resuming delayed broadcast
D/PMS     (  902): acquireWL(424058b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1326 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1326/10029)
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360022497
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023013
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023132
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023138
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023143
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360027424
D/PMS     (  902): releaseWL(424058b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  902): acquireWL(4278d428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1326 10029 WorkSource{10029 com.google.android.gms}
D/MtpReceiver( 2165): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2165): [MTP][handleMessage][startService]
D/MtpReceiver( 2165): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2165): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2165): [MTP][handleMessage]-
D/ConnectivityService(  902): getActiveNetworkInfo called by  (1326/10029)
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360022497
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023013
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023132
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023138
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360023143
W/AlarmManager(  902): Converted elapesd time is over 1 year! when = 315360027424
D/PMS     (  902): releaseWL(4278d428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/MtpService( 2165): [MTP] startForeground
I/RemoteViews( 1105): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1105): com.android.providers.media 2 1 10
I/RemoteViews( 1105): com.android.providers.media (false,0)
I/ActivityManager(  902): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3325 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews.Performance( 1105): com.android.providers.media 1 2 15
D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2165): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2165): TotalSize=1918604,MediaCacheLimit=6000
D/PMS     (  902): acquireWL(425ad0d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1956 10029 null
D/MtpService( 2165): [isMtpConnected] connected: true
D/SyncApplication( 3325): Loading default preferences
I/iu.UploadsManager( 1956): End new media; added: 0, uploading: 0, time: 58 ms
D/PMS     (  902): releaseWL(425ad0d8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
W/Resources( 3325): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/Process (  902): killProcessQuiet, pid=2853
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 2853:com.android.settings/1000 (adj 15): empty #17
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 2853
D/WifiService(  902): New client listening to asynchronous messages
D/SyncApplication( 3325): Overriding preferences with custom values
D/SyncApplication( 3325): Updating preferences succeeded
E/SyncApplication( 3325): Application created.
D/VolumeInfo( 3325): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3325): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3325): Found 0 mount point(s)
V/VolumeInfo( 3325): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3325): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3325): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3325): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3325): getNewCalendarAuthority()...
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3325, uid=10008, userID:0
W/PackageManager(  902): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3325): enableAppOperation()+
D/SyncApplication( 3325): enableAppOperation()-
D/HTCUtilities( 3325): isNeorSinged() + 
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3325, uid=10008, userID:0
W/PackageManager(  902): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3325): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3325): isNeorSinged() return false
D/CDMountReceiver( 3325): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3325): USB connected to PC
D/FOTAReceiver( 3325): onReceive() enter 
D/FOTAReceiver( 3325): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  902): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3345 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  902): killProcessQuiet, pid=3092
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  902): Killing 3092:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/HtcFingerPrintQuickLaunchProvider( 3345): -onCreate()
V/Settings:HtcSettingsApplication( 3345): [3345/3345] onCreate()
D/TetherSettings( 3345): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3345): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3345): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3345): Cust_ConnectToPC   : spcsc>false
D/        ( 3345): Cust_ConnectToPC   : IPT>true
,D/        ( 3345): Cust_ConnectToPC   : Singel_USB>false
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  902): Recipient 3092
W/Settings( 3345): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3345): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3345): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3345): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3345): Cust_ConnectToPC   : spcsc>false
D/        ( 3345): Cust_ConnectToPC   : IPT>true
D/        ( 3345): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3345): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3345): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3345): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3345): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3345): usb_cable_connect = 1
D/SmartNS_Utility( 3345): usb_denied = 0
I/SmartNS_NSReceiver( 3345): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3345): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3345): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3345): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3345): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3345): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3345):  defaultType:0
I/SmartNS_PSService( 3345): fail notificaiton:false
D/SmartNS_Utility( 3345): usb_cable_connect = 1
D/SmartNS_Utility( 3345): usb_denied = 0
I/SmartNS_PSService( 3345): usb notificaiton:true
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  902): bSetPropertyMultiRAB:false
D/ConnectivityService(  902): getActiveNetworkInfo called by com.android.settings (3345/1000)
I/ActivityManager(  902): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/SmartNS_Utility( 3345): usb_cable_connect = 1
D/SmartNS_Utility( 3345): usb_denied = 0
I/SmartNS_PSService( 3345): usb notificaiton:true
,V/Tethering(  902): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1105): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1105): com.android.settings 0 1 10
I/ActivityManager(  902): Resuming delayed broadcast
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.android.settings (3345/1000)
D/Tethering(  902): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  902): bSetPropertyMultiRAB:false
D/SmartNS_Utility( 3345): usb_cable_connect = 1
,D/SmartNS_Utility( 3345): usb_denied = 0
,D/DotMatrix( 1531): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/ActivityManager(  902): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1105): com.android.settings (true,33751552),
I/RemoteViews.Performance( 1105): com.android.settings 1 1 10
I/SmartNS_PSService( 3345): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3345): USB Plugged, Set USBPlugged=  truePSenabled:false
,W/WeatherUtility( 3202): can't get weather sync account
I/ActivityManager(  902): Resuming delayed broadcast
,D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1244): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1244): com.google.android.googlequicksearchbox 1 0 5
,I/ActivityManager(  902): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3362 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/WeatherRequest( 3202): request cur loc, but there is no sys cur
,W/Settings( 3202): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1244): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1244): com.htc.widget.weatherclock 0 83 17
,W/ContextImpl( 3362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3362): call getInstance()
I/ActivityManager(  902): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3362): MY_DEBUG = false
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,I/dalvikvm-heap(  902): Grow heap (frag case) to 17.522MB for 143088-byte allocation
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,W/BatSI   (  902): Couldn't get kernel wake lock stats
,I/ActivityManager(  902): Resuming delayed broadcast
,D/PMS     (  902): acquireWL(4283bdb0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3362 1000 null
,D/Process (  902): killProcessQuiet, pid=3131
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  902): Killing 3131:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/WeatherUtility( 1105): can't get weather sync account
I/ActivityManager(  902): Recipient 3131
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WeatherUtility( 1294): Weather sync is On
,D/PMS     (  902): releaseWL(4283bdb0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1216): MSG_NOTIFY_CS_TO_SYNC <<
,D/WSP     ( 1294): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/WeatherUtility( 3202): can't get weather sync account
I/ActivityManager(  902): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3379 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherRequest( 3202): request cur loc, but there is no sys cur
,W/Settings( 3202): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1244): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1244): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1244): com.htc.widget.weatherclock 1 8 17
,I/ActivityManager(  902): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3397 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  902): killProcessQuiet, pid=3143
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3143:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3143
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3397): Database version: 95
,V/AlarmManager(  902): sending alarm PendingIntent{424a8d10: PendingIntentRecord{426859f0 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1447782153498, Int=0
,W/ContextImpl( 3397): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3397): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3397): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,D/Process (  902): killProcessQuiet, pid=3187
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  902): Killing 3187:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  902): Recipient 3187
,I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3397): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3397): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  351): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3397, uid=10154, userID:0
,D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
,D/MediaRouterService(  902): Client com.google.android.music (pid 3397): Registered
,I/MediaRouter( 3397): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  902): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  902):     Client/Owner: Client
D/WifiDisplayAdapter(  902):     GroupId: 
D/WifiDisplayAdapter(  902):     Passphrase: 
D/WifiDisplayAdapter(  902):     SessionId: 0
D/WifiDisplayAdapter(  902):     IP Address: }
,D/DFPI.PIReciver( 3217): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3217): onHandleIntent
,I/DFPI.ApkInstallService( 3217): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3217): check CID = HTC__032
,I/DFPI.ApkInstallService( 3217): There is no Demo.apk in sd card or phone storage
D/ConnectivityService(  902): getActiveNetworkInfo called by com.google.android.music (3397/10154)
I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/MediaRouter( 3397): getSelectedRoute
I/PackageManager(  902):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3397, uid=10154, userID:0
D/ConnectivityService(  902): getActiveNetworkInfo called by  (902/1000)
D/PMS     (  902): acquireWL(424dfba0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 902 1000 null
I/ActivityManager(  902): Resuming delayed broadcast
D/PMS     (  902): releaseWL(424dfba0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  902): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3419 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  902): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.musicenhancer (3419/10053)
,E/cutils  (  351): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  351): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3419): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,D/BluetoothManagerService(  902): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  902): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  902): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  902): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  902): Settings:Agentvalue: 0
,W/Settings:Agent(  902): >> traceCallingStack()
,W/Settings:Agent(  902): Process.myPid(): 902
W/Settings:Agent(  902): Process.myTid(): 1344
,W/Settings:Agent(  902): Process.myUid(): 1000
W/Settings:Agent(  902): 
,W/Settings:Agent(  902): 
,W/System.err(  902): java.lang.Throwable: stack dump
,W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  902): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  902): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  902): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  902): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  902): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  902): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  902): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  902): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  902): 
,W/Settings:Agent(  902): << traceCallingStack(): 18(ms)
,D/BluetoothManagerService(  902): Message: MESSAGE_DISABLE
,D/WifiManager( 2944): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
,W/HtcDLNAServiceManager(  902): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  902): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  902): Settings:Agentvalue: 0
,W/Settings:Agent(  902): >> traceCallingStack()
,W/Settings:Agent(  902): Process.myPid(): 902
,W/Settings:Agent(  902): Process.myTid(): 1241
,W/Settings:Agent(  902): Process.myUid(): 1000
,W/Settings:Agent(  902): 
D/WifiService(  902): New client listening to asynchronous messages
D/WifiService(  902): setWifiEnabled: false pid=2944, uid=10396
E/WifiService(  902): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  902): isSprintWifiRestricted(): false
I/WifiService(  902): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  902): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  902): 
W/System.err(  902): java.lang.Throwable: stack dump
W/System.err(  902): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  902): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  902): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  902): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  902): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  902): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  902): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  902): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  902): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  902): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  902): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  902): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  902): 
W/Settings:Agent(  902): << traceCallingStack(): 9(ms)
I/jxcore-log( 2944): ****TEST TOOK:  5083  ms ****
I/jxcore-log( 2944): 
I/jxcore-log( 2944): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2944): 
,E/cutils-trace( 3439): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 3439): ====startRecUseTime====
D/htc.customization.log.level( 3439):  is 
,W/CustomizationLogLevel( 3439): Level value is invalid, use default level 2
,I/HtcModeClient( 1480): handler message = 4011
,E/HtcModeClient( 1480): Check connection and retry 5 times.
,D/CustomizationManager( 3439):  Read ACC file spent 0.061 (s)
,D/CIDMapFileReader( 3439): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3439): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3439): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3439): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3439): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3439): Parsing tag item name = HTC__J15
,D/CIDMapFileReader( 3439): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3439): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3439): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3439): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3439): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3439): Parsing tag category name = system
,I/CustomizationCIDLoader( 3439): Parsing tag category name = application
I/CustomizationCIDLoader( 3439): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3439): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3439): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3439): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3439): Parsing tag category name = Settings
D/CustomizationManager( 3439):  Read CID file spent 0.107 (s)
,D/CustomizationManager( 3439):  All configurations done spent 0.108 (s)
W/HtcNativeFlag( 3439): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3439): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3439): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3439): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  902): deletePackageAsUser: pkg=com.example.hello, pid=3439, uid=2000 user=0
,I/ActivityManager(  902): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  902): killProcessQuiet, pid=2944
D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  902): Copying FileAsset 0x6a66ce60 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  902): Killing 2944:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  902): Force removing ActivityRecord{424718a8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  902): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  902): Skipping PackageSetting{4229f310 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  902): Force stopping com.example.hello appid=10396 user=0: pkg removed
,W/InputDispatcher(  902): channel '42657480 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  902): channel '42657480 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  902): Attempted to unregister already unregistered input channel '42657480 com.example.hello.MainActivity (s)'
I/WindowState(  902): WIN DEATH: Window{42657480 u0 com.example.hello/com.example.hello.MainActivity}
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  902): Client connection lost with reason: 4
I/FeedHostManager( 1244): [onResume]
I/FeedProviderManager( 1244): onResume
I/SocialFeedProvider( 1244): +onResume
I/SocialFeedProvider( 1244): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1244): -onResume
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1531): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1105): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1531): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1531): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/WindowManager(  902): WINDOW DIED Window{42657480 u0 com.example.hello/com.example.hello.MainActivity}
,W/GeofencerStateMachine( 1194): Ignoring removeGeofence because network location is disabled.
,D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  902): acquireWL(4298dc50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1194 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  902): getActiveNetworkInfo called by com.htc.launcher (1244/10076)
I/ConnectivityHelper( 1244): [getCurrentConnectionType] no network connection
,W/SystemReader( 1228): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  902): releaseWL(4298dc50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "sms"
,I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1244): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  902): Resuming delayed broadcast
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "mms"
,E/ExternalAccountType( 1317): Unsupported attribute readOnly
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "mmsto"
,D/Process (  902): killProcessQuiet, pid=2838
,D/Process (  902): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/ActivityManager(  902): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3452 uid=10081 gids={50081, 5001, 1028, 1015}
I/ActivityManager(  902): Killing 2838:com.android.settings:remote/1000 (adj 15): empty #17
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "sms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
I/DisplayManagerService(  902): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  902): Recipient 2838
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "smsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "mms"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/PackageManager(  902):   Action: "android.intent.action.SENDTO"
I/PackageManager(  902):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  902):   Scheme: "mmsto"
I/PackageManager(  902): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1216 :
,I/InputMethodManagerService(  902): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/PhoneApp( 1216): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/SoundPicker( 3452): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3452): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3452): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3452): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3452): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3452): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  902): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
W/InputMethodManagerService(  902): Got RemoteException sending setActive(false) notification to pid 2944 uid 10396
,I/InputMethodManagerService(  902): Enable input method client, pid=1244
I/SensorManager(  902): mEventCount = 300
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3452): MODE_GSM access default DB
W/Binder  ( 1182): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1182): java.lang.NullPointerException
W/Binder  ( 1182): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1182): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1182): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1182): 	at dalvik.system.NativeStart.run(Native Method)
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3452): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3452): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3452): MODE_GSM access default DB
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3452): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3452): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3452): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3452): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  902): Resuming delayed broadcast
,I/ActivityManager(  902): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,W/PackageManager(  902): Unable to load service info ResolveInfo{42876988 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  902): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  902): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  902): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  902): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  902): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  902): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  902): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  902): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  902): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  902): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  902): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  902): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  902): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,W/AtomicFile(  902): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/RemoteDisplayProvider(  902): start
W/AppWidgetServiceImpl(  902): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/ActivityManager(  902): Resuming delayed broadcast
,D/DFPI.PIReciver( 3217): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3217): onHandleIntent
,I/DFPI.ApkInstallService( 3217): Media Scan Finished Case 
I/ActivityManager(  902): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/DFPI.ApkInstallService( 3217): check CID = HTC__032
,I/DFPI.ApkInstallService( 3217): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  902): Resuming delayed broadcast
I/ActivityManager(  902): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SocialFeedProvider( 1244): +disConnect socialManager
,I/SocialFeedProvider( 1244): disconnect socialManager
,I/SocialFeedProvider( 1244): -disConnect socialManager

```
