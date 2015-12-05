#### Test 50388019f33194e_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm-heap( 1239): Grow heap (frag case) to 12.416MB for 2097144-byte allocation
D/AppTag  ( 3252): getInstance(Context context)
D/AppTag  ( 3252): getInstance(Context context)
D/AppTag  ( 3252): onCreate()
D/QXDM2SD:HtcNative( 1239): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
D/Process (  906): killProcessQuiet, pid=2946
--------- beginning of /dev/log/system
I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3270 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2946:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/HtcCupdXmlParser( 3237): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  906): Recipient 2946
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/AlarmManager(  906): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  906): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  906): [AlarmQueuing] init alarm queuing list
V/Settings:HtcSettingsApplication( 3270): [3270/3270] onCreate()
W/ContextImpl( 3270): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3284 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3295 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=2914
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2914:com.android.vending/u0a73 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2914
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcFingerPrintQuickLaunchProvider( 3295): -onCreate()
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@423ab5f0
V/Settings:HtcSettingsApplication( 3295): [3295/3295] onCreate()
D/Process (  906): killProcessQuiet, pid=2962
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  906): Killing 2962:com.htc.showme/u0a82 (adj 15): empty #17
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42757af8
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2962
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@423cd650
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  906): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
D/Process (  906): killProcessQuiet, pid=2976
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  906): Killing 2976:com.htc.updater/u0a84 (adj 15): empty #17
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 2976
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TetherSettings( 3295): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3295): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3295): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3295): Cust_ConnectToPC   : spcsc>false
D/        ( 3295): Cust_ConnectToPC   : IPT>true
D/        ( 3295): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3295): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3295): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3295): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3295): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3295): Cust_ConnectToPC   : spcsc>false
D/        ( 3295): Cust_ConnectToPC   : IPT>true
D/        ( 3295): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3295): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3295): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3295): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3295): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 3295): setISNotification
D/SmartNS_Utility( 3295): usb_cable_connect = 1
D/SmartNS_Utility( 3295): usb_denied = 0
I/SmartNS_PSService( 3295): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3295/1000)
D/SmartNS_Utility( 3295): usb_cable_connect = 1
D/SmartNS_Utility( 3295): usb_denied = 0
I/SmartNS_PSService( 3295): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3295/1000)
D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  906): killProcessQuiet, pid=3016
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3016:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/RemoteViews( 1119): com.android.settings (true,33751552)
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e76688 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1119): com.android.settings 2 15 0 10
I/ActivityManager(  906): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3314 uid=9987 gids={49987}
I/RemoteViews( 1119): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1119): com.android.settings 1 0 10
I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42695860, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42695860, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b27ab0
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@421484a8
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@42695860
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42695860, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{4277cfb0 u0 ReceiverList{4277cf50 906 system/1000/u0 local:42666e00}}
E/cutils-trace( 3282): Error opening trace file: No such file or directory (2)
D/NfcUiccLockService( 3314): -- To check whether previous opened channel needed to be closed ...
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 3
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42695860, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b27ab0
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@421484a8
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@42695860
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/Process (  906): killProcessQuiet, pid=3065
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3335 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 3065:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3016
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3065
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  906): killProcessQuiet, pid=3085
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3347 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3085:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3085
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3282): ====startRecUseTime====
D/htc.customization.log.level( 3282):  is 
W/CustomizationLogLevel( 3282): Level value is invalid, use default level 2
I/GAV2    ( 2990): Thread[GAThread,5,main]: No campaign data found.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2611/10028)
D/PMS     (  906): releaseWL(423e1080): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/CustomizationManager( 3282):  Read ACC file spent 0.075 (s)
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3282): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3282): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3282): Parsing tag category name = system
I/CustomizationCIDLoader( 3282): Parsing tag category name = application
I/CustomizationCIDLoader( 3282): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3282): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3282): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3282): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3282): Parsing tag category name = Settings
D/CustomizationManager( 3282):  Read CID file spent 0.125 (s)
D/CustomizationManager( 3282):  All configurations done spent 0.125 (s)
W/HtcNativeFlag( 3282): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3282): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3282): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3282): Fail to get flag for type 'language', use default value: -1
I/SensorManager(  906): mEventCount = 300
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3282
D/PMS     (  906): acquireHCC(427e92f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
W/asset   (  906): Copying FileAsset 0x632af410 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1113291792
D/PMS     (  906): acquireHCC(426683a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
D/PMS     (  906): acquireWL(42674110): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d30758
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3368 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
W/asset   ( 3368): Copying FileAsset 0x5c82a428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/YouTube ( 3347): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/TrimMemoryManager( 1269): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3368): Binding Chromium to main looper Looper (main, tid 1) {41adb478}
I/LibraryLoader( 3368): Expected native library version number "",actual native library version number ""
I/chromium( 3368): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3368): Initializing chromium process, renderers=0
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424acf48:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): acquireWL(4275ea68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
V/AlarmManager(  906): sending alarm PendingIntent{41ecf800: PendingIntentRecord{41eb7370 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=48695, Int=259200000
V/AlarmManager(  906): sending alarm PendingIntent{41e10138: PendingIntentRecord{4242f048 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49993, Int=0
D/PMS     (  906): acquireWL(4277c270): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(4275ea68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 3368): 1101991536: getState(). Returning 12
I/Adreno-EGL( 3368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3368): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3368): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3368): Local Branch: 
I/Adreno-EGL( 3368): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3368): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3368):                  aa63bbd948f41d15fc72f585e
D/libc    ( 3347): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3347): [NET] getaddrinfo-, SUCCESS
W/chromium( 3368): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/YouTube ( 3347): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
W/dalvikvm( 3368): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3368): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3368): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3368): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3368): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3368): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3368): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3368): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3368): CordovaWebView is running on device made by: HTC
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3347/10168)
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3347): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/AwContents( 3368): nativeOnDraw failed; clearing to background color.
D/YouTube ( 3347): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +256ms
W/ResourceType( 3368): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3368): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b22320, mServedView=org.apache.cordova.engine.SystemWebView{41ae8190 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Disable input method client, pid=1269
I/InputMethodManagerService(  906): Enable input method client, pid=3368
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/YouTube ( 3347): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
W/AwContents( 3368): nativeOnDraw failed; clearing to background color.
D/PMS     (  906): releaseWL(42674110): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/YouTube ( 3347): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3347): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3347): Registered
I/MediaRouter( 3347): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.youtube (3347/10168)
D/YouTube ( 3347): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3347): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449275244&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 3347): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3347): [NET] getaddrinfo-,err=8
D/libc    ( 3347): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3347): [NET] getaddrinfo-, 1
D/libc    ( 3347): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4f49 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/AndroidProtocolHandler( 3368): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3368): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3347): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3347): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3347): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/MediaRouter( 3347): getSelectedRoute
D/YouTube ( 3347): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3347): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/YouTube ( 3347): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3347/10168)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=96
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3347): [NET] getaddrinfo_proxy-, success
D/YouTube ( 3347): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3347/10168)
D/YouTube ( 3347): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3347): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.a.d
D/YouTube ( 3347): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
W/BroadcastQueue(  906): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3347/10168)
D/YouTube ( 3347): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.offline.a.d
D/JsMessageQueue( 3368): Set native->JS mode to OnlineEventsBridgeMode
D/AutoSetting( 1433): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3295): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3295): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3295): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3295): Cust_ConnectToPC   : spcsc>false
D/        ( 3295): Cust_ConnectToPC   : IPT>true
D/        ( 3295): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3295): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3295): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3295): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3295): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1433): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/PSReceiver( 3295): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3295): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3295): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3295):  defaultType:0
W/ContextImpl( 3295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/WeatherUtility( 1119): can't get weather sync account
D/YouTube ( 3347): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service
I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3448 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/YouTube ( 3347): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
D/YouTube ( 3347): apps.youtube.datalib.offline.b.run:86 Dispatching stored offline request immediately.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3347/10168)
I/GoogleConversionPing( 3347): Ping responded with response code 200
D/browser ( 3448): Browser versionCode = 760001523 versionName = 7.0.2512153020
D/jxcore_app_log( 3368): JniHelper::setJavaVM(0x415ab048), pthread_self() = 1658295312
D/JX-Cordova( 3368): jxcore cordova android initializing
E/dalvikvm( 3347): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3347): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3347): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3347): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3347): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
W/SWE_UI  ( 3448): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3448): Loading: swewebviewchromium
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/WeatherRequest( 1119): request cur loc, but there is no sys cur
I/LibraryLoader( 3448): Time to load native libraries: 37 ms (timestamps 4986-5023)
I/LibraryLoader( 3448): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3448): Initializing chromium process, renderers=9
I/LibraryLoader( 3448): Expected native library version number "",actual native library version number ""
I/chromium( 3448): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.htc.aurora
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1250): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
W/jxcore-log( 3368): Initializing JXcore engine
W/jxcore-log( 3368): JXcore engine is ready
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
W/jxcore-log( 3368): Starting JXcore engine
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/ProviderInstaller( 3347): Installed default security provider GmsCore_OpenSSL
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/libc    ( 3347): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 4
D/libc    ( 3347): [NET] getaddrinfo-,err=8
D/libc    ( 3347): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    ( 3347): [NET] getaddrinfo-, 1
D/libc    ( 3347): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =639 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=83
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3347): [NET] getaddrinfo_proxy-, success
I/global  ( 3347): call createSocket() return a new socket.
D/libc    ( 3347): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
D/libc    ( 3347): [NET] getaddrinfo-, SUCCESS
W/jxcore-log( 3368): Platform android
W/jxcore-log( 3368): 
W/jxcore-log( 3368): Process ARCH arm
W/jxcore-log( 3368): 
I/Adreno-EGL( 3448): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3448): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3448): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3448): Local Branch: 
I/Adreno-EGL( 3448): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3448): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3448):                  aa63bbd948f41d15fc72f585e
I/jxcore-log( 3368): JXcore Cordova bridge is ready!
I/jxcore-log( 3368): 
W/jxcore-log( 3368): JXcore engine is started
D/Process (  906): killProcessQuiet, pid=3097
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1298): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  906): Killing 3097:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/SIMStateChangeReceiver( 1514): SIM state: ABSENT
I/SIMStateChangeReceiver( 1514): phoneType = 0
I/SIMStateChangeReceiver( 1514): remove notification
I/ActivityManager(  906): Recipient 3097
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/jxcore-log( 3368): >> HTC-HTC Desire 820
E/jxcore-log( 3368): 
I/jxcore-log( 3368): Total memory 1964650496
I/jxcore-log( 3368): 
I/jxcore-log( 3368): Free memory 638345216
I/jxcore-log( 3368): 
I/jxcore-log( 3368): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3368): 
I/jxcore-log( 3368): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3368): 
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3489 uid=10031 gids={50031, 3003, 5012}
I/jxcore-log( 3368): userPath [ 'www' ]
I/jxcore-log( 3368): 
I/jxcore-log( 3368): Size 720 1184
I/jxcore-log( 3368): 
I/jxcore-log( 3368): Screen Brightness 10
I/jxcore-log( 3368): 
E/jxcore-log( 3368): Dummy Error Log.
E/jxcore-log( 3368): 
W/PackageManager(  906): Unable to load service info ResolveInfo{42500ea0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
D/Process (  906): killProcessQuiet, pid=2489
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3501 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2489:com.android.defcontainer/u0a19 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2489
W/SystemReader( 2875): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2875): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2875): onReceive()
D/ExchangePolicystatus( 2875): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2875): onReceive(): else
D/Process (  906): killProcessQuiet, pid=3129
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1239): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  906): Killing 3129:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3516 uid=10038 gids={50038}
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3531 uid=10077 gids={50077}
D/Process (  906): killProcessQuiet, pid=3166
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3166:com.htc.backup/1000 (adj 15): empty #17
W/AccTypeManager( 3501): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3501): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/SMSBackup( 3531): Got a database change event
D/AccTypeManager( 3501): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3129
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3545 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/Process (  906): killProcessQuiet, pid=3112
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3112:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
E/ExternalAccountType( 3501): Unsupported attribute readOnly
D/RemoteDisplayProvider(  906): start
W/AccTypeManager( 3501): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3501): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/CalendarApplication( 3545): onCreate
D/ProviderChangeReceiver( 3545): ---------------------------------------------------
D/ProviderChangeReceiver( 3545): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3545): start to updateAlertNotification!
D/AccTypeManager( 3501): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/ContextImpl( 3270): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3545): No fired or scheduled alerts
D/HtcAlertUtils( 3545): -- cancelReminderNotification --
D/HtcAlertUtils( 3545): broadcastExistReminder!
D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
E/ExternalAccountType( 3501): Unsupported attribute readOnly
D/Process (  906): killProcessQuiet, pid=3193
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3193:com.google.android.talk/u0a111 (adj 15): empty #17
I/AdsMeasurementBroadcastReceiver( 2611): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 2611): Unauthorized to start the main service
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
I/ActivityManager(  906): Recipient 3166
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3563 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
I/ActivityManager(  906): Recipient 3112
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherUtility( 3563): can't get weather sync account
I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3578 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/DemoRecovery.RestoreReceiver( 3578): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/WeatherRequest( 3563): request cur loc, but there is no sys cur
W/Settings( 3563): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 3578): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/RestoreService( 3578): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3193
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 0 8 17
D/Process (  906): killProcessQuiet, pid=3222
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3592 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3222:com.htc.backupreset/1000 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3222
,D/PMS     (  906): acquireWL(426777c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3592 10070 null
,D/PMS     (  906): acquireWL(42750df0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3592 10070 null
,D/PMS     (  906): releaseWL(426777c0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3592): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/TodoTaskNotifyService( 3592): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(42750df0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,W/NotifyReceiver( 3592): stopSelfResult true
,D/Process (  906): killProcessQuiet, pid=3237
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3607 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  906): Killing 3237:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3237
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3619 uid=10081 gids={50081, 3003, 5012}
I/jxcore-log( 3368): getBuffer is called!!!!
I/jxcore-log( 3368): 
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3631 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3284
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  906): killProcessQuiet, pid=3252
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3284:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  906): Killing 3252:com.zoodles.kidmode/u0a149 (adj 15): empty #18
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3252
,I/MusicStore( 3631): Database version: 95
,W/ContextImpl( 3631): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3631): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/ActivityManager(  906): Recipient 3284
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3631): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3631): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3631): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3631, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 3631): Registered
,I/MediaRouter( 3631): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,I/NetworkMonitor( 3631): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3631/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1999/10021)
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=17 [17][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3652 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3631): getSelectedRoute
,I/NetworkMonitor( 3631): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3631/10154)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/MessagingNotification( 2875): New incoming message, can't cancel notification now
,D/MessagingNotification( 2875): newMsgCnt: 0, false
,D/Process (  906): killProcessQuiet, pid=3314
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3631, uid=10154, userID:0
,I/ActivityManager(  906): Killing 3314:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Recipient 3314
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 3652): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3652): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3652): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 3652): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3652): Preparing secondary program dexes.
V/DexLibLoader( 3652): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3652): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3652): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3652): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3652): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 3652): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3652): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3652): Dex already copied
D/OdexVerifier( 3652): Odex verification is skipped.
V/DexLibLoader( 3652): Creating class loader
V/DexLibLoader( 3652): Finished creating class loader
,V/DexLibLoader( 3652): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3652): Dex already copied
D/OdexVerifier( 3652): Odex verification is skipped.
,V/DexLibLoader( 3652): Creating class loader
V/DexLibLoader( 3652): Finished creating class loader
V/DexLibLoader( 3652): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3652): Dex already copied
D/OdexVerifier( 3652): Odex verification is skipped.
,V/DexLibLoader( 3652): Creating class loader
,V/DexLibLoader( 3652): Finished creating class loader
V/DexLibLoader( 3652): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 3652): Dex already copied
D/OdexVerifier( 3652): Odex verification is skipped.
,V/DexLibLoader( 3652): Creating class loader
,V/DexLibLoader( 3652): Finished creating class loader
,V/DexLibLoader( 3652): Verifying classes from secondary dexes.
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(427e92f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(426683a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/DexLibLoader( 3652): DexLibLoader.ensureDexLoaded took 83 ms
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b66dd0 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,I/ActivityManager(  906): Killing 3335:com.android.smith/u0a163 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3335
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3335
,E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b66dd0 -
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/dalvikvm( 3652): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3652): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3652): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3652): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3652): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3652): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3652): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): releaseWL(4277c270): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/dalvikvm( 3652): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3652): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 3652): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 3652): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3652/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3652): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3652): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3652): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3347
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3347:com.google.android.youtube/u0a168 (adj 15): empty #17
D/PMS     (  906): acquireWL(427224d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2611 10028 null
,D/PMS     (  906): acquireWL(426f8a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2611 10028 null
,D/PMS     (  906): releaseWL(427224d8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 2611): Disabling old GoogleServicesFramework version
,I/CheckinService( 2611): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2611, uid=10028, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2611, uid=10028, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2611/10028)
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/PMS     (  906): releaseWL(426f8a38): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1433): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2611/10028)
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3677 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1433): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1433): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1433): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1433): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1433): service - handleMessage() setting current location null
D/AutoSetting( 1433): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1433): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1433/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1433/10053)
,W/fb4a(:<default>):UserScope( 3652): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3652): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/ActivityManager(  906): Recipient 3347
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3347): Died!
,W/fb4a(:<default>):UserScope( 3652): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 3677): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3677): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3677): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3677): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3694 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3295
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3295:com.android.settings/1000 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3677/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3677/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3677/10078)
,D/PMS     (  906): acquireWL(4266f638): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2611 10028 null
I/ActivityManager(  906): Recipient 3295
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 3652): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/PMS     (  906): acquireWL(426017c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2611 10028 null
,D/PMS     (  906): releaseWL(4266f638): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2611/10028)
,I/CheckinService( 2611): Preparing to send checkin request
,I/EventLogService( 2611): Accumulating logs since 1449273950081
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3712 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  906): sending alarm PendingIntent{41ee8770: PendingIntentRecord{41f77398 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53790, Int=0
,I/dalvikvm-heap( 3652): Grow heap (frag case) to 9.960MB for 84664-byte allocation
,I/dalvikvm-heap( 3652): Grow heap (frag case) to 9.973MB for 28144-byte allocation
,E/dalvikvm( 3652): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3652): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3652): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3652): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3652): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3652): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3652): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3652): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3652): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3652): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3652): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,I/HtcModeClient( 1514): handler message = 4011
W/dalvikvm( 3652): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/HtcModeClient( 1514): Check connection and retry 5 times.
W/dalvikvm( 3652): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3652): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3652): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3652): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3652): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3652): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3725 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3448
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3448:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/dalvikvm-heap( 3652): Grow heap (frag case) to 10.044MB for 39954-byte allocation
I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3738 uid=10091 gids={50091, 3003, 5012}
,I/dalvikvm-heap( 3652): Grow heap (frag case) to 10.121MB for 79892-byte allocation
W/EventLogAggregator( 2611): Unknown tag: install_package_attempt
W/EventLogAggregator( 2611): Unknown tag: snet
,W/EventLogAggregator( 2611): Unknown tag: snet_gcore
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3725): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3725): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  906): Recipient 3448
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 3725): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3725): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3725): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/GoogleHttpClient( 2611): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 2611): Using GMS GoogleHttpClient
D/MdScBoot( 3712): [a80.1.] 30@-012658 -> 40@-012728
,D/Process (  906): killProcessQuiet, pid=3489
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  906): Killing 3489:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=3501
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3501:com.htc.contacts/u0a41 (adj 15): empty #17
D/WifiService(  906): New client listening to asynchronous messages
I/ActivityManager(  906): Recipient 3489
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3501
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2611/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [4][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2611/10028)
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,I/dalvikvm-heap( 3652): Grow heap (frag case) to 10.283MB for 75760-byte allocation
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3652/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42393b38 u0 ReceiverList{41e820b8 3652 com.facebook.katana/10026/u0 remote:41ec81a0}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42393b38 u0 ReceiverList{41e820b8 3652 com.facebook.katana/10026/u0 remote:41ec81a0}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42383a08 u0 ReceiverList{41e48908 3652 com.facebook.katana/10026/u0 remote:41e852c0}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3725/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3652/10026)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3652/10026)
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,V/WebViewChromiumFactoryProvider( 3725): Binding Chromium to main looper Looper (main, tid 1) {41ad6130}
,I/LibraryLoader( 3725): Expected native library version number "",actual native library version number ""
,I/chromium( 3725): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3725): Initializing chromium process, renderers=0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3652/10026)
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,E/AudioManagerAndroid( 3725): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(423127d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(42022ee8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(423127d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  906): acquireWL(4236f238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1485 10028 null
D/PMS     (  906): releaseWL(4236f238): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/Adreno-EGL( 3725): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3725): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3725): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3725): Local Branch: 
I/Adreno-EGL( 3725): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3725): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3725):                  aa63bbd948f41d15fc72f585e
,I/GoogleHttpClient( 1371): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1371): Using GMS GoogleHttpClient
,D/GCoreFlp( 1485): Unknown pending intent to remove.
W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
D/PMS     (  906): acquireWL(4241d888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1485 10028 null
,D/PMS     (  906): releaseWL(4241d888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/NSApplication( 3725): Starting up...
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3725/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3725/10151)
,I/NotificationStore( 1371): System rebooted after Notification storage file was last written
,I/NotificationStore( 1371): Deleting the file
D/Process (  906): killProcessQuiet, pid=3516
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3781 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  906): Killing 3516:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3516
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/CheckinRequestBuilder( 2611): awaiting user notification for token
D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41b216a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 8 2 12
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3652): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3652): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3797 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3781/10160)
,D/Process (  906): killProcessQuiet, pid=3531
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3781/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3781/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3781/10160)
D/PMS     (  906): acquireWL(426a6858): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3781 10160 null
,I/ActivityManager(  906): Killing 3531:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/MultiDex( 3797): install
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 3797): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,D/AlertReceiver( 3545): beginStartingService
,I/MultiDex( 3797): loading existing secondary dex files
,I/MultiDex( 3797): load found 1 secondary dex files
I/ActivityManager(  906): Recipient 3531
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(42672830): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3781 10160 null
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/MultiDex( 3797): install done
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(4263fd38): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3545 10013 null
D/PMS     (  906): releaseWL(426a6858): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/PMS     (  906): acquireWL(41d09d78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2611 10028 null
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(41d09d78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/ProviderInstaller( 3797): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/AlertService( 3545): start to updateAlertNotification!
D/PMS     (  906): releaseWL(42672830): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/PMS     (  906): acquireWL(42678ad0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3592 10070 null
,D/PMS     (  906): acquireWL(427eebf0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3592 10070 null
,D/PMS     (  906): releaseWL(42678ad0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/WeatherUtility( 3563): can't get weather sync account
,D/AlertService( 3545): No fired or scheduled alerts
,D/HtcAlertUtils( 3545): -- cancelReminderNotification --
,D/HtcAlertUtils( 3545): broadcastExistReminder!
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3592): update TASK shortcut>
I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3829 uid=10090 gids={50090, 3003, 5012, 1028}
,D/PMS     (  906): releaseWL(4263fd38): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
I/TodoTaskNotifyService( 3592): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/AlertReceiver( 3545): stopSelfResult true
,W/WeatherRequest( 1119): request cur loc, but there is no sys cur
,I/TodoTaskNotifyService( 3592): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/WeatherRequest( 3563): request cur loc, but there is no sys cur
,W/Settings( 3563): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/PMS     (  906): releaseWL(427eebf0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3592): stopSelfResult true
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/WorldClock.Global( 3829): isHtcDevice = true
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 9 17
,I/WorldClock.Global( 3829): isHtcDevice = true
W/ContextImpl( 3270): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/WorldClock.AlarmUtils( 3829): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3829): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3829): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1119): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3844 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/TimeService( 3844): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449275249233
,D/Process (  906): killProcessQuiet, pid=3578
,I/ActivityManager(  906): Killing 3578:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/AdsMeasurementBroadcastReceiver( 2611): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 2611): Unauthorized to start the main service
,I/FeedHostManager( 1269): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
D/PMS     (  906): acquireWL(425ff900): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1269 10075 null
D/PMS     (  906): releaseWL(425ff900): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
I/ActivityManager(  906): Recipient 3578
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3859 uid=10038 gids={50038}
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3872 uid=10077 gids={50077}
,D/Process (  906): killProcessQuiet, pid=2875
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2875:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/SMSBackup( 3872): Got a database change event
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3885 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  906): killProcessQuiet, pid=3607
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3607:com.htc.stock/u0a81 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3607
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2875
,I/ImageRamCache( 3885): create image Cache, size: 31457280.
I/ImageRamCache( 3885): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3885): create image Cache, size: 12582912.
,I/FeedSettings( 3885): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3885): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3885): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3885): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3885): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3885): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3885): [custom highlight] onReceive
,D/CustomHighlightService( 3885): [custom highlight] onHandleIntent
,D/NewsDB  ( 3885): set custom highlight []
I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3885): [custom highlight] set tags 
,D/Process (  906): killProcessQuiet, pid=3619
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3619:com.htc.stock:remote/u0a81 (adj 15): empty #17
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Recipient 3619
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Resuming delayed broadcast
D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=3903 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,D/MessageFrequencyProvider( 3903): onCreate
,V/GetPrviateResource( 3903): GetPrviateResource
,V/GetPrviateResource( 3903): GetPrviateResource
,D/MessageCustFlag( 3903): sense_version=6.0
,D/BTAccessoryUtil( 3903): createReceiver
,D/BTAccessoryUtil( 3903): registerReceiver return intent = null
D/MessageCustFlag( 3903): sku_id=99
,W/SystemReader( 3903): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 3903): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3903): networkCode: 
D/MessageCustFlag( 3903): sku_id=99
,D/MmsConfig( 3903): SIE smsPri: null
,D/MmsConfig( 3903): networkCode: 
,D/HtcTelephonyCapability( 3903): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 3903): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3903): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3903): Cannot find qct_8960_interface, use default value instead
,D/MmsConfig( 3903): packageName: com.htc.vvm.att does not exist
,D/MessagingShortcutReceiver( 3903): keep hiding shortcut bubble
,D/MessagingShortcut( 3903): updateMsgShortcut, msg count> -1
,D/SettingsManager( 3903): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41addb88
D/MessagingShortcut( 3903): After query: 0
D/MessagingShortcut( 3903): mPresentUnreadCount: -1
,D/MessagingShortcut( 3903): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 3903): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] reorderNotification, total:0
D/DotMatrix( 1569): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3592): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1239): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  906): killProcessQuiet, pid=3631
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3631:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,D/MdScBoot( 3712): [f68.1.] 40@-012728
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  906): Resuming delayed broadcast
,D/MtpReceiver( 1999): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 1999): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 1999): [MTP][handleMessage][startService]
,D/MtpReceiver( 1999): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 1999): [MTP][handleMessage]-
,D/MtpService( 1999): [MTP] startForeground,
I/RemoteViews( 1119): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1119): com.android.providers.media 1 0 10
,I/RemoteViews( 1119): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1119): com.android.providers.media 1 1 15
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3923 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/MtpService( 1999): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 1999): TotalSize=1918604,MediaCacheLimit=6000
D/PMS     (  906): acquireWL(424601b0): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3781 10160 null
,D/MtpService( 1999): [isMtpConnected] connected: true
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3631
,D/SyncApplication( 3923): Loading default preferences
D/MediaRouterService(  906): Client com.google.android.music (pid 3631): Died!
,W/Resources( 3923): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/dalvikvm-heap( 3781): Grow heap (frag case) to 15.220MB for 1821008-byte allocation
,D/WifiService(  906): New client listening to asynchronous messages
,I/Adreno-EGL( 3797): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3797): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3797): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3797): Local Branch: 
I/Adreno-EGL( 3797): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3797): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3797):                  aa63bbd948f41d15fc72f585e
,D/SyncApplication( 3923): Overriding preferences with custom values
,D/SyncApplication( 3923): Updating preferences succeeded
,E/SyncApplication( 3923): Application created.
D/VolumeInfo( 3923): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3923): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3923): Found 0 mount point(s)
,V/VolumeInfo( 3923): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3923): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3923): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3923): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3923): getNewCalendarAuthority()...
,D/SyncApplication( 3923): enableAppOperation()+
,D/SyncApplication( 3923): enableAppOperation()-
,D/HTCUtilities( 3923): isNeorSinged() + 
D/PMS     (  906): releaseWL(424601b0): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3923, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3923, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3923): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3923): isNeorSinged() return false
,D/CDMountReceiver( 3923): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3923): USB connected to PC
,D/Process (  906): killProcessQuiet, pid=3652
,I/ActivityManager(  906): Killing 3652:com.facebook.katana/u0a26 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/FOTAReceiver( 3923): onReceive() enter 
D/FOTAReceiver( 3923): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3948 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3677
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3677:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/Adreno-EGL( 3797): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3797): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3797): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3797): Local Branch: 
I/Adreno-EGL( 3797): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3797): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3797):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 3797): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3797): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3797): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3797): Local Branch: 
I/Adreno-EGL( 3797): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3797): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3797):                  aa63bbd948f41d15fc72f585e
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3652
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3677
,D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(422e0418): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1485 10028 null
,D/PMS     (  906): acquireWL(420c8940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1485 10028 null
,D/PMS     (  906): releaseWL(422e0418): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(420c8940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,W/Settings( 3797): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/HtcFingerPrintQuickLaunchProvider( 3948): -onCreate()
,V/Settings:HtcSettingsApplication( 3948): [3948/3948] onCreate()
,D/TetherSettings( 3948): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3948): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3948): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3948): Cust_ConnectToPC   : spcsc>false
D/        ( 3948): Cust_ConnectToPC   : IPT>true
,D/        ( 3948): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3948): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3948): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3948): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3948): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3948): Cust_ConnectToPC   : spcsc>false
D/        ( 3948): Cust_ConnectToPC   : IPT>true
D/        ( 3948): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3948): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3948): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3948): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3948): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3948): usb_cable_connect = 1
,D/SmartNS_Utility( 3948): usb_denied = 0
I/SmartNS_NSReceiver( 3948): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3948): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3948): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3948): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3948): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3948):  defaultType:0
I/SmartNS_PSService( 3948): fail notificaiton:false
D/SmartNS_Utility( 3948): usb_cable_connect = 1
D/SmartNS_Utility( 3948): usb_denied = 0
I/SmartNS_PSService( 3948): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3948/1000)
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3948): usb_cable_connect = 1
D/SmartNS_Utility( 3948): usb_denied = 0
,I/SmartNS_PSService( 3948): usb notificaiton:true
,I/RemoteViews( 1119): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1119): com.android.settings 4 1 10
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3948): usb_cable_connect = 1
,D/SmartNS_Utility( 3948): usb_denied = 0
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3948/1000)
,D/DotMatrix( 1569): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1119): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1119): com.android.settings 2 1 10
I/SmartNS_PSService( 3948): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3948): USB Plugged, Set USBPlugged=  truePSenabled:false
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3797/10028)
I/ActivityManager(  906): Resuming delayed broadcast
,W/WeatherUtility( 3563): can't get weather sync account
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/RemoteViews( 1269): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1269): com.google.android.googlequicksearchbox 1 1 5
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
W/WeatherRequest( 3563): request cur loc, but there is no sys cur
,W/Settings( 3563): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CustomHighlightReceiver( 3885): [custom highlight] onReceive
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,I/ActivityManager(  906): Resuming delayed broadcast
D/WifiNative-wlan0(  906):    returned true
D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1269): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1269): pl.k2.droidoaudioteka 2 0 8
D/CustomHighlightService( 3885): [custom highlight] onHandleIntent
,D/NewsDB  ( 3885): set custom highlight []
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 5 17
,D/CustomHighlightService( 3885): [custom highlight] set tags 
,I/ActivityManager(  906): Resuming delayed broadcast
,D/CustomHighlightReceiver( 3885): [custom highlight] onReceive
D/CustomHighlightService( 3885): [custom highlight] onHandleIntent
,D/NewsDB  ( 3885): set custom highlight []
I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3885): [custom highlight] set tags 
,D/SMSBackup( 3872): Got a database change event
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42450860): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42587b98 mBinding = false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1463
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 5(ms)
D/PMS     (  906): releaseWL(42450860): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): acquireWL(42540e18): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1514 10014 null
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/PMS     (  906): releaseWL(42540e18): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
I/ActivityManager(  906): Resuming delayed broadcast
D/BluetoothManagerService(  906): Sending off request.
D/BluetoothAdapterState( 1595): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1595): Setting state to 13
I/BluetoothAdapterState( 1595): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1595): Broadcasting updateAdapterState() to 1 receivers.
D/WifiManager( 3368): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 1595): onBluetoothDisable()
I/bt-btif ( 1595): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1595): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 1595): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 1595): BTM_SetDiscoverability
I/bt-btm  ( 1595): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1595): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1595): br_edr_supported=0x0
I/bt-btm  ( 1595): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1595): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/BluetoothAdapterProperties( 1595): Scan Mode:20
D/BluetoothAdapterState( 1595): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/bt-btm  ( 1595): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1595): btm_ble_update_adv_flag old=0x0
I/bt-btif ( 1595): BTA_JvDeleteRecord
I/bt-btif ( 1595): BTA_JvRfcommStopServer
D/bt-btm  ( 1595): BTM_FreeSCN 
I/bt-btif ( 1595): BTA_JvDeleteRecord
I/bt-btif ( 1595): BTA_JvRfcommStopServer
D/bt-btm  ( 1595): BTM_FreeSCN 
I/bt-btif ( 1595): BTA_JvDeleteRecord
I/bt-btif ( 1595): BTA_JvRfcommStopServer
D/bt-btm  ( 1595): BTM_FreeSCN 
I/bt-btif ( 1595): BTA_JvDeleteRecord
I/bt-btif ( 1595): BTA_JvRfcommStopServer
D/bt-btm  ( 1595): BTM_FreeSCN 
I/bt-btif ( 1595): BTA_JvDeleteRecord
I/bt-btif ( 1595): BTA_JvRfcommStopServer
D/bt-btm  ( 1595): BTM_FreeSCN 
I/bt-btif ( 1595): BTA_JvDeleteRecord
I/bt-btif ( 1595): BTA_JvRfcommStopServer
D/bt-btm  ( 1595): BTM_FreeSCN 
E/BtOppRfcommListener( 1595): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btm  ( 1595): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1595): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1595): BTM_SetConnectability
I/bt-btm  ( 1595): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1595): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1595): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 1595): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1595): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1595): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1595): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1595): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1595): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1595): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1595): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1595): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1595): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1595): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1595): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1595): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1595): Write Extended Inquiry Response to controller
I/bt-btm  ( 1595): Write Extended Inquiry Response to controller
I/bt-btm  ( 1595): Write Extended Inquiry Response to controller
I/bt-btm  ( 1595): Write Extended Inquiry Response to controller
I/bt-btm  ( 1595): BTM_SetDiscoverability
I/bt-btm  ( 1595): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1595): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1595): br_edr_supported=0x0
I/bt-btm  ( 1595): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1595): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1595): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1595): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1595): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1595): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1595): BTM_SetConnectability
I/bt-btm  ( 1595): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1595): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1595): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1595): BTM_IsInquiryActive
I/bt-btm  ( 1595): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1595): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1595): BTM_FreeSCN 
I/bt-btm  ( 1595): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1595): BTM_FreeSCN 
I/bt-btm  ( 1595): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1595): AVRC_Close handle:0
D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1356
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:4
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: false pid=3368, uid=10355
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/bt-sdp  ( 1595): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1595): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1595): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1595): GATT_Deregister gatt_if=3
I/bt-att  ( 1595): GATT_Deregister gatt_if=4
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 2(ms)
V/BluetoothSapService( 1595): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  906): Bluetooth State Change Intent: 12 -> 13
I/IntentController( 1119): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 1595): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1595): ***********state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1777): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41afb160
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1777): onDeInitialized
D/BluetoothMasReceiver( 1595): Bluetooth STATE CHANGED to 13
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1777): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1777): getNotificationManager
V/BluetoothSapReceiver( 1595): SapReceiver onReceive 
V/BluetoothSapReceiver( 1595): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1595):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 1595): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1595): Pbap Service closeService in
V/BluetoothPbapService( 1595): successfully stopped pbap service
V/BluetoothPbapService( 1595): Pbap Service closeService out
V/BluetoothSapService( 1595): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1595): state: 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1777): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1777):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1777): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1777): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1777): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1777):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1777): deinit: 0
D/BluetoothAdapter( 1595): 1102002576: getState(). Returning 13
V/BluetoothSapService( 1595): Stopping SAP server process
D/PMS     (  906): acquireWL(42353118): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3948 1000 null
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1777): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1777): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1777): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1777): Exit IdleState
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1777): setPendingRequestAlarm: false, mContext = null, null
D/BluetoothManagerService(  906): Message: MESSAGE_UNREGISTER_ADAPTER
I/jxcore-log( 3368): ****TEST TOOK:  5103  ms ****
I/jxcore-log( 3368): 
I/jxcore-log( 3368): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3368): 
D/WirelessDisplayService(  906): getMirrorDisplayStatus:falsecurState:1
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1152): Power_Mode_Type mode = 0
I/wpa_supplicant( 1152): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/BluetoothManagerService(  906): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4235d058:true
D/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
V/BluetoothSapService( 1595): Sap Service closeSapService in
V/BluetoothSapService( 1595): Close listen Socket : 
V/BluetoothSapService( 1595): Close rfcomm Socket : 
V/BluetoothSapService( 1595): Close sapd  Socket : 
,V/BluetoothSapReceiver( 1595): BluetoothSapReceiver deinit
D/PMS     (  906): releaseWL(42353118): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(42353310): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3976 uid=10037 gids={50037, 3002, 3001}
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): acquireWL(425d3cd0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3948 1000 null
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42530658:true
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3948): new LocationAgent instance!!
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothSapService( 1595): successfully stopped Sap service
V/BluetoothSapService( 1595): Sap Service closeSapService out
I/BtOppRfcommListener( 1595): stopping Accept Thread
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19940 mDataStallAlarmIntent=PendingIntent{41e10308: PendingIntentRecord{42447e20 android broadcastIntent}}
D/HtcTagManager( 3948): HtcTagManager construction complete
I/BtOppRfcommListener( 1595): BluetoothSocket listen thread finished
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
V/BluetoothPbapService( 1595): Pbap Service onDestroy
V/BluetoothPbapService( 1595): Pbap Service closeService in
V/BluetoothPbapService( 1595): Pbap Service closeService out
V/BluetoothSapService( 1595): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b2d800
V/BluetoothSapService( 1595): Sap Service closeSapService in
V/BluetoothSapService( 1595): Close listen Socket : 
V/BluetoothSapService( 1595): Close rfcomm Socket : 
V/BluetoothSapService( 1595): Close sapd  Socket : 
D/PackageBroadcastService( 2611): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/QuickSettingBluetooth( 1119): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1119): removeIcon slot=bluetooth index=12 viewIndex=0
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/BluetoothAdapter( 3948): 1102416400: getState(). Returning 13
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/WifiP2pService(  906): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothInputDevice( 3948): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
V/BluetoothSapService( 1595): Sap Service closeSapService out
V/BluetoothSapService( 1595): ***onDestroyed***
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
D/BluetoothAdapter( 3948): 1102416400: getState(). Returning 13
D/BluetoothInputDevice( 3948): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3948): Bluetooth service connected
,W/BluetoothInputDevice( 3948): Proxy not attached to service
D/WifiStateMachine(  906): Call handleNetworkDisconnect() in SupplicantStoppingState
D/BluetoothPan( 3948): BluetoothPan()
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1152): Power_Mode_Type mode = 0
I/wpa_supplicant( 1152): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/BluetoothManagerService(  906): Registered receivers: 8
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiP2pService(  906): P2pDisablingState
D/WifiP2pService(  906): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): p2p socket connection lost
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiP2pService(  906): P2pDisabledState
D/WifiDisplayController(  906): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  906): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  906): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  906): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  906): P2pDisabledState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  906): updateConnection
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
I/WifiDisplayController(  906): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  906): updateConnection enter step 4
D/WifiDisplayController(  906): Failed to set WFD info with reason 2.
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
V/AudioService(  906): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  906):     Client/Owner: Client
V/AudioService(  906):     GroupId: 
V/AudioService(  906):     Passphrase: 
V/AudioService(  906):     SessionId: 0
V/AudioService(  906):     IP Address: }
D/HtcEffectManagerBase(  906): onEventChanged id=5 status=false
D/HtcEffectManager(  906): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  906): convertEffect before=902
,D/HtcEffectManager(  906): convertEffect after=902
D/BluetoothAdapter( 3948): 1102416400: getState(). Returning 13
,D/BluetoothPan( 3948): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 3948): Bluetooth service connected
D/BluetoothMap( 3948): Create BluetoothMap proxy object
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 9
E/BluetoothMap( 3948): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiNative-p2p0(  906): doBoolean: TERMINATE
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  906): QCOM Debug wifi_send_command "TERMINATE"
,E/wpa_supplicant( 1152): Supplicant Terminat @ wpa_supplicant_deinit function
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3948): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Registered receivers: 10
D/wpa_supplicant( 1152): TDLS: Tear down peers
I/wpa_supplicant( 1152): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiNative-p2p0(  906):    returned true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/HtcBtWidget_BTWidgetProvider( 3976): onBTStateChanged() for widget: 
,D/BluetoothPbap( 3948): BluetoothPbap()
I/IntentController( 1119): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/HtcBtWidget_BTWidgetProvider( 3976): updateWidget(context) for widget: 
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 11
D/BluetoothAdapter( 3948): 1102416400: getState(). Returning 13
D/BluetoothPbap( 3948): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3948): Bluetooth service connected
,D/LocalBluetoothProfileManager( 3948): LocalBluetoothProfileManager construction complete
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1119): updateWifiState: WIFI_STATE_CHANGED disabled
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1595): Shutdown
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,D/DockEventReceiver( 3948): finishStartingService: stopping service
,D/BluetoothMasReceiver( 1595): Bluetooth STATE CHANGED to 13
,I/CheckinTask( 2611): Sending checkin request (8916 bytes)
,D/WISPrService( 3948): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3948): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1777): Received state change = 13
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1152): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/PMS     (  906): releaseWL(425d3cd0): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/WifiService(  906): New client listening to asynchronous messages
I/wpa_supplicant( 1152): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1152): TDLS: Remove peers on disassociation
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2462
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb860cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1152):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1152): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1152): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1152): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1152): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1152): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest,(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1152): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1152): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1152): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WISPrService( 3948): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3948): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1777): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41afb160
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onDestroy() called...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): deinitLeServices: null
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/PMS     (  906): acquireWL(4266b580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=-5ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/libc    (  364): [NET] entry_id:6   entry:0xb8bd6200  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb8bd5d90  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb8bd6818  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb8bd66f0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8bd5fd8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb8bd6108  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb8bd62e0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8bd6410  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): acquireWL(427ceb80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  906): releaseWL(427ceb80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(4238b150): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1119): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,D/Process (  906): killProcessQuiet, pid=3694
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
W/ActivityThread( 2611): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(427b5fe0): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
I/ActivityManager(  906): Killing 3694:com.android.chrome/u0a96 (adj 15): empty #17
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,I//system/bin/ip(  364): RTNETLINK answers: No such process
D/PMS     (  906): releaseWL(4238b150): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): releaseWL(427b5fe0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1371/10028)
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): releaseWL(4266b580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
I/PeopleContactsSync( 2611): CP2 sync disabled
,D/Process (  906): killProcessQuiet, pid=3725
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3725:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2611, uid=10028, userID:0
,D/libc    ( 2611): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2611): [NET] getaddrinfo-,err=8
D/libc    ( 2611): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2611): [NET] getaddrinfo-, 1
,D/libc    ( 2611): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =354e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/libc    (  364): [NET]Querying server xid =354e (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  364): [NET]res_nsend:ECONNREFUSED
D/libc    (  364): [NET] -----res_nsend exit-1: xid=354e, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  364): [NET]res_queryN: exit 2
D/libc    (  364): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
,D/libc    ( 2611): [NET] getaddrinfo_proxy-
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1371/10028)
W/bt-btif ( 1595): ag scb idx 1 not allocated
E/CheckinTask( 2611): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/bt-btif ( 1595): ag scb idx 2 not allocated
E/bt-btif ( 1595): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1595): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1595): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1595): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1595): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1595): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1595): L2CAP - PSM: 0x0017 not found for deregistration
,W/GoogleHttpClient( 2611): Unable to close GMS GoogleHttpClient
I/ActivityManager(  906): Recipient 3694
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2611/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2611/10028)
,D/PMS     (  906): releaseWL(426017c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2611): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ba7a40 that was originally bound here
E/ActivityThread( 2611): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ba7a40 that was originally bound here
E/ActivityThread( 2611): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2611): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2611): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2611): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2611): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2611): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2611): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2611): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2611): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2611): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2611): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2611): 	at bks.a(SourceFile:298)
E/ActivityThread( 2611): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2611): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2611): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2611): 	at java.lang.Thread.run(Thread.java:864)
,E/bt_userial_mct( 1595): userial_close userial_thread_created userial_running is 1 
,I/ActivityManager(  906): Recipient 3725
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1152): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1152): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 1152): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 1152): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1152): nl80211: Unsubscribe mgmt frames handle 0xb860d718 (mode change)
I/wpa_supplicant( 1152): htc_wext_command_deinit +
I/wpa_supplicant( 1152): htc_wext_command_deinit -
E/wpa_supplicant( 1152): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1152): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1152): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1152): TDLS: Tear down peers
I/wpa_supplicant( 1152): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1152): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1152): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
,I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x62b0d5d8
I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x62b0d6c0
W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  906): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  906): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  906):    returned false
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  906): WIFI Trun OFF
,D/WirelessDisplayService(  906): getDiscoveryDongleList
E/cutils-trace( 3995): Error opening trace file: No such file or directory (2)
,I/IntentController( 1119): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,E/WifiStateMachine(  906): [MLHD] Error! unhandled message 6 { when=-11ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1119): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3948): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3948): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  906): acquireWL(427aac30): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4018 uid=10031 gids={50031, 3003, 5012}
,I/QuickSettingWifi( 1119): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3738
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3738:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1433): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1433): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Recipient 3738
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4034 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/CustomizationManager( 3995): ====startRecUseTime====
D/htc.customization.log.level( 3995):  is 
,W/CustomizationLogLevel( 3995): Level value is invalid, use default level 2
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4034, uid=10073, userID:0
,D/Finsky  ( 4034): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4034/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4034/10073)
,I/bt-btif ( 1595): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 1595): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1595): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 1595): Stopping profile services that were post enabled
,D/BluetoothHeadset( 1119): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
D/BluetoothPhoneService( 1239): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
,I/QuickSettingMiniLite( 1119): btListener.disconnect:HEADSET
D/BluetoothHeadset(  906): Proxy object disconnected
,D/A2dpService( 1595): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1595): doQuit
,D/A2dpStateMachine( 1595): Exit Disconnected: -1
,D/BluetoothA2dp(  906): Proxy object disconnected
,D/HidService( 1595): Received stop request...Stopping profile...
,D/Finsky  ( 4034): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/CustomizationManager( 3995):  Read ACC file spent 0.055 (s)
,D/CIDMapFileReader( 3995): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3995): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3995): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3995): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3995): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3995): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3995): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3995): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3995): Parsing tag item name = HTC__002
D/HealthService( 1595): Received stop request...Stopping profile...
,D/CIDMapFileReader( 3995): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3995): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3995): Parsing tag category name = system
D/PanService( 1595): Received stop request...Stopping profile...
D/PanService( 1595): stop
D/PanService( 1595): stop: mTetherAc send disconnect
,I/CustomizationCIDLoader( 3995): Parsing tag category name = application
I/CustomizationCIDLoader( 3995): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 3995): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3995): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3995): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3995): Parsing tag category name = Settings
D/CustomizationManager( 3995):  Read CID file spent 0.097 (s)
,D/CustomizationManager( 3995):  All configurations done spent 0.098 (s)
,D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECT
,W/Settings( 4034): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4034): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECTED
W/HtcNativeFlag( 3995): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3995): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3995): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3995): Fail to get flag for type 'language', use default value: -1
,E/BluetoothTethering(  906): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  906): BluetoothPAN Proxy object disconnected
,D/BtGatt.DebugUtils( 1595): handleDebugAction() action=null
D/BtGatt.GattService( 1595): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1595): stop()
,D/BluetoothAdapterService( 1595): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 1595): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1595): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 1595): Profile still running: com.android.bluetooth.hdp.HealthService
,D/A2dpStateMachine( 1595): cleanup
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4034, uid=10073, userID:0
D/Avrcp   ( 1595): Unregistering previous receiver
D/BluetoothAdapterService( 1595): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1595): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1595): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1595): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1595): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1595): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1595): Cleaning up Bluetooth Health object
D/PanService( 1595): CMD_CHANNEL_DISCONNECTED
D/PanService( 1595): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1595): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1595): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1595): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1595): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1595): Setting state to 10
I/BluetoothAdapterState( 1595): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1595): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothSap( 3948): onBluetoothStateChange on: false
I/BluetoothAdapterState( 1595): Entering OffState
D/BluetoothHeadset(  906): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1119): onBluetoothStateChange: up=false
E/BluetoothPan( 3948): 
E/BluetoothPan( 3948): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41b66ea0
E/BluetoothPan( 3948): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3948): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3948): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3948): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3948): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3948): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3948): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothA2dp(  906): onBluetoothStateChange: up=false
D/BluetoothMap( 3948): onBluetoothStateChange: up=false
E/BluetoothMap( 3948): 
E/BluetoothMap( 3948): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41b68220
E/BluetoothMap( 3948): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3948): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3948): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3948): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3948): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3948): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3948): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothInputDevice( 3948): onBluetoothStateChange: up=false
E/BluetoothInputDevice( 3948): 
E/BluetoothInputDevice( 3948): java.lang.IllegalArgumentExcept,ion: Service not registered: android.bluetooth.BluetoothInputDevice$2@41b65908
E/BluetoothInputDevice( 3948): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3948): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3948): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3948): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3948): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3948): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3948): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothPbap( 3948): onBluetoothStateChange: up=false
E/BluetoothPbap( 3948): 
E/BluetoothPbap( 3948): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41b6e338
E/BluetoothPbap( 3948): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3948): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3948): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3948): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3948): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3948): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3948): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1830): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bd6cb8
D/BluetoothAdapter( 1830): onBluetoothServiceDown: done
D/BluetoothAdapter( 1119): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ec9668
D/BluetoothAdapter( 1119): onBluetoothServiceDown: done
D/BluetoothAdapter( 1485): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c2fe08
D/Process (  906): killProcessQuiet, pid=3545
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/BluetoothAdapter( 1485): onBluetoothServiceDown: done
D/BluetoothAdapter( 1239): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d6e6e8
D/BluetoothAdapter( 1239): onBluetoothServiceDown: done
,D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_ADDED
D/BluetoothAdapter( 1595): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41af1e00
D/BluetoothDevice( 1595): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1595): onBluetoothServiceDown: done
D/BluetoothAdapter(  906): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42587b98
,D/BluetoothAdapter(  906): onBluetoothServiceDown: done
D/BluetoothAdapter( 3368): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41af18d8
,D/BluetoothAdapter( 3368): onBluetoothServiceDown: done
,I/ActivityManager(  906): Killing 3545:com.htc.calendar/u0a13 (adj 15): empty #17
D/BluetoothAdapter( 1250): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41babba0
D/Finsky  ( 4034): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4034): [1] 2.run: Finished loading 1 libraries.
,D/BluetoothAdapter( 1250): onBluetoothServiceDown: done
D/BluetoothAdapter( 3948): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b59478
,D/BluetoothAdapter( 3948): onBluetoothServiceDown: done
D/BluetoothAdapter( 1777): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41afba30
,D/BluetoothAdapter( 1777): onBluetoothServiceDown: done
D/BluetoothManagerService(  906): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42587b98 mBinding = false
,D/BluetoothManagerService(  906): Sending unbind request.
,D/BluetoothAdapterService( 1595): Cleaning up adapter native....
I/bt-btif ( 1595): HAL bt_hal_cbacks->thread_evt_cb
D/BluetoothAdapterService( 1595): Done cleaning up adapter native....
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService(1101984400)( 1595): ****onDestroy()********
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3545
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2990): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/IntentController( 1119): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NfcHandover( 1250): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/BtGatt.GattService( 1595): cleanup()
W/bt-btif ( 1595): GATTC Module not enabled/already disabled
W/bt-btif ( 1595): GATTS Module not enabled/already disabled
D/LocalBluetoothProfileManager( 3948): setBluetoothStateOff
D/HtcTagManager( 3948): stopProxy
,W/BluetoothEventManager( 3948): unregister mProfileBroadcastReceiver fail
,D/BluetoothMasReceiver( 1595): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 1595): onDestroy: mIsEmailEnabled: true
D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=3995, uid=2000 user=0
,D/TetherPref( 3948): persistRestoreBluetoothState false
D/PMS     (  906): acquireWL(427754a8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3948 1000 null
W/ContextImpl( 3948): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  906): releaseWL(427754a8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  906): acquireWL(426374b8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3948 1000 null
D/DockEventReceiver( 3948): finishStartingService: stopping service
,D/HtcBtWidget_BTWidgetProvider( 3976): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3976): updateWidget(context) for widget: 
,D/PMS     (  906): releaseWL(426374b8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
W/BluetoothHeadset( 1119): Proxy not attached to service
,I/QuickSettingMiniLite( 1119): updateLiteState:no connect device!
D/PMS     (  906): acquireWL(4267ce70): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=3368
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 3368:com.example.hello/u0a355 (adj 0): stop com.example.hello
,W/asset   (  906): Copying FileAsset 0x63a98e10 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
W/ActivityManager(  906): Force removing ActivityRecord{427d56d0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/PackageSettings(  906): Skipping PackageSetting{4225f138 com.test.thalitest/10348} due to missing metadata
,D/BluetoothAdapter( 1119): 1104688352: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1119): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,W/InputDispatcher(  906): channel '42611098 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '42611098 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42611098 com.example.hello.MainActivity (s)'
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/WindowState(  906): WIN DEATH: Window{42611098 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=0: pkg removed
I/WindowManager(  906): WINDOW DIED Window{42611098 u0 com.example.hello/com.example.hello.MainActivity}
,I/FeedHostManager( 1269): [onResume]
,I/FeedProviderManager( 1269): onResume
I/SocialFeedProvider( 1269): +onResume
I/SocialFeedProvider( 1269): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1269): -onResume
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
I/acms    ( 1887): Unregistering com.example.hello
,E/acms    ( 1887): Could not unregister removed application com.example.hello
,W/GeofencerStateMachine( 1485): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 3885): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3885): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PMS     (  906): acquireWL(427508a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1485 10028 null
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1269/10075)
,I/ConnectivityHelper( 1269): [getCurrentConnectionType] no network connection
,D/BluetoothMasReceiver( 1595): Bluetooth STATE CHANGED to 10
D/Process (  906): killProcessQuiet, pid=3829
D/PMS     (  906): releaseWL(427508a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/ActivityManager(  906): Killing 3829:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3829
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,D/Finsky  ( 4034): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3368 uid 10355
I/InputMethodManagerService(  906): Enable input method client, pid=1269
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/ActivityManager(  906): Delaying start of: ServiceRecord{42677a50 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/SystemReader( 1250): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1777): Received state change = 10
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PMS     (  906): releaseWL(4267ce70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422fdf80:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3270): new LocationAgent instance!!
,D/HtcTagManager( 3270): HtcTagManager construction complete
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Finsky  ( 4034): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/BluetoothAdapter( 3270): 1102102840: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 3270): BluetoothInputDevice()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothAdapter( 3270): 1102102840: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  906): Registered receivers: 12
D/BluetoothInputDevice( 3270): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3270): Bluetooth service connected
,W/BluetoothInputDevice( 3270): Proxy not attached to service
,D/BluetoothPan( 3270): BluetoothPan()
D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 13
D/BluetoothAdapter( 3270): 1102102840: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3270): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 3270): Bluetooth service connected
,D/BluetoothMap( 3270): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 14
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,E/BluetoothMap( 3270): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1485/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1830/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1887/1000)
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/BluetoothSap( 3270): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 15
W/ContextImpl( 3270): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothPbap( 3270): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 16
D/BluetoothAdapter( 3270): 1102102840: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3270): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3270): Bluetooth service connected
D/LocalBluetoothProfileManager( 3270): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3270): 1102102840: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3270): 1102102840: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3270): setBluetoothStateOff
D/HtcTagManager( 3270): stopProxy
,W/BluetoothEventManager( 3270): unregister mProfileBroadcastReceiver fail
,D/Process (  906): killProcessQuiet, pid=3844
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4079 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  906): Killing 3844:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/PMS     (  906): acquireWL(42757d50): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
,I/ActivityManager(  906): Recipient 3844
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(42022ee8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  906): releaseWL(42757d50): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DeviceManagement( 4079): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4079 dbg=false s=true
,I/DeviceManagement( 4079): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  906): killProcessQuiet, pid=3903
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/PMS     (  906): acquireWL(425c07f0): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
I/ActivityManager(  906): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/ActivityManager(  906): Killing 3903:com.htc.sense.mms/u0a64 (adj 15): empty #17
,W/Netd    (  364): No subsystem found in netlink event
,V/Tethering(  906): remove iface:wlan0
D/Tethering(  906): interfaceRemoved wlan0
,E/Tethering(  906): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
I/ActivityManager(  906): Recipient 3903
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(425c07f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4092 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(425fe340): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
,D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): acquireWL(42733020): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(42733020): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  906): releaseWL(425fe340): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4263ffe8): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
,W/Netd    (  364): No subsystem found in netlink event
,V/Tethering(  906): remove iface:p2p0
D/Tethering(  906): interfaceRemoved p2p0
,E/Tethering(  906): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,W/PackageManager(  906): Unable to load service info ResolveInfo{42775868 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  906): releaseWL(4263ffe8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4232efd8): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(4232efd8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4266a9e0): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
,D/PMS     (  906): releaseWL(4266a9e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425e3b90): PARTIAL_WAKE_LOCK  Icing 0x1 2611 10028 null
,D/PMS     (  906): releaseWL(425e3b90): PARTIAL_WAKE_LOCK  Icing 0x1 null
,E/SQLiteLog( 2990): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2990): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x644ac088
E/IcingCorporaProvider( 2990): Exception thrown from registerCorpora
E/IcingCorporaProvider( 2990): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2990): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2990): 	at apd.a(PG:171)
E/IcingCorporaProvider( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.b(PG:415)
E/IcingCorporaProvider( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.k(PG:369)
E/IcingCorporaProvider( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:286)
E/IcingCorporaProvider( 2990): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2990): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2990): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2990): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2990): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2990): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2990): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2990): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2990): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2990): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2990): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2990): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2990): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2990): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2990): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2990): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2990): 	at apf.call(PG:156)
E/IcingCorporaProvider( 2990): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2990): 	... 14 more
,W/IcingCorporaProvider( 2990): Corpora registration failed
,V/AlarmManager(  906): sending alarm PendingIntent{41ff4a48: PendingIntentRecord{426a17b8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449275252043, Int=0
,E/SQLiteLog( 2990): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2990): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x644ac088
,W/dalvikvm( 2990): threadid=27: thread exiting with uncaught exception (group=0x416a3e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
,E/RollingFileStream( 4034): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
E/AndroidRuntime( 2990): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2990): Process: com.google.android.googlequicksearchbox:search, PID: 2990
E/AndroidRuntime( 2990): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2990): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2990): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2990): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2990): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2990): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2990): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2990): 	at cid.d(PG:186)
E/AndroidRuntime( 2990): 	at clo.g(PG:594)
E/AndroidRuntime( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2990): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2990): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2990): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2990): 	at clr.tL(PG:827)
E/AndroidRuntime( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2990): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2990): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2990): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2990): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4092): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4092): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4092): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4092): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4092): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4092): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4092): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4092): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4092): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4092): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4092): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4092): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4092): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4092): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4092): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4092): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4092): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4092): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4092): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4092): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4092): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4092): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4092): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4092): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4092): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4092): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4092): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4092): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4092): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4092): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4092): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4092): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4092): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4092): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4092): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4092): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4092): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4092): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4092): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4092): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4092): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4092): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4092): threadid=11: thread exiting with uncaught exception (group=0x416a3e30)
,E/AndroidRuntime( 4092): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4092): Process: com.google.android.apps.docs, PID: 4092
E/AndroidRuntime( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4092): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4092): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4092): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4092): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4092): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4092): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4092): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4092): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4092): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4092): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4092): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4092): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4092): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4092): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4092): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4092): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4092): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4092): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4092): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4092): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4092): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4092): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4092): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4092): Opened ClientFlag.db in read-only mode
,I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4114 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAV2    ( 4092): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4092): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/SQLiteDatabase( 4092): 	at aid.a(DatabaseModelLoader.java:340)
E/SQLiteDatabase( 4092): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/SQLiteDatabase( 4092): 	at fv.run(DocsApplication.java:288)
E/AbstractDatabaseInstance( 4092): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AbstractDatabaseInstance( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AbstractDatabaseInstance( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AbstractDatabaseInstance( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AbstractDatabaseInstance( 4092): 	at ahs.getWritableDatabase(DatabaseHe,lper.java:236)
E/AbstractDatabaseInstance( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AbstractDatabaseInstance( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AbstractDatabaseInstance( 4092): 	at azJ.a(Suppliers.java:125)
E/AbstractDatabaseInstance( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/AbstractDatabaseInstance( 4092): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4092): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4092): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4092): 	at fv.run(DocsApplication.java:288)
,W/dalvikvm( 4092): threadid=12: thread exiting with uncaught exception (group=0x416a3e30)
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4092): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4092): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4092): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4092): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4092): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4092): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4092): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime_2_crash( 4092): crash in the same process: Background initialization thread
E/AndroidRuntime_2_crash( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteDatabase.,open(SQLiteDatabase.java:829)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime_2_crash( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime_2_crash( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime_2_crash( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime_2_crash( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime_2_crash( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime_2_crash( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime_2_crash( 4092): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime_2_crash( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/AndroidRuntime_2_crash( 4092): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime_2_crash( 4092): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime_2_crash( 4092): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime_2_crash( 4092): 	at fv.run(DocsApplication.java:288)
,W/BroadcastQueue(  906): Skipping deliver [background] BroadcastRecord{425d5ec8 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{425d5d08 4092 com.google.android.apps.docs/10100/u0 remote:4276e8d0}: process crashing
,I/htcbackup-core( 4114): ModelRegistry: Loading model meta data from resources...
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/ContextImpl( 4114): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 4114): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  906): Delay finish: com.htc.backup/.task.restore.PackageInstallReceiver
I/DeviceManagement( 4079): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 4079): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.usage, com.htc.backupreset, com.htc.autobot.cargps.provider, android, com.htc.lockscreen, com.htc.android.htcloglevel, com.htc.htcpowermanager, com.htc.android.htcsetupwizard, com.htc.guide, com.android.CSDFunctionG, com.android.inputdevices, com.htc.backup, com.htc.mirrorlinkserver, com.android.location.fused, com.android.settings, com.htc.drive.activator, com.android.providers.settings, com.qualcomm.privinit, com.htc.cirmodule, com.qualcomm.timeservice, com.htc.checkinprovider, com.htc.feedback, com.htc.smartdim, com.android.keychain, com.htc.home.personalize]
I/DeviceManagement( 4079): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,W/Finsky  ( 4034): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/ActivityManager(  906): Delaying start of: ServiceRecord{427f56b8 u0 com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService}
D/Finsky  ( 4034): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
E/SQLiteDatabase( 4034): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4034): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4034): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4034): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:235)
E/SQLiteDatabase( 4034): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4034): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4034): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4034): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4034): threadid=25: thread exiting with uncaught exception (group=0x416a3e30)
,E/ActivityManager(  906): App crashed! Process: com.android.vending
E/AndroidRuntime( 4034): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4034): Process: com.android.vending, PID: 4034
E/AndroidRuntime( 4034): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4034): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4034): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4034): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4034): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4034): 	at com.google.android.finsky.library.Libraries$3.run(Libraries.java:235)
E/AndroidRuntime( 4034): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4034): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4034): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4034): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4092): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4092): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4092): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4092): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4092): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4092): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4092): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4092): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4092): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4092): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4092): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4092): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4092): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4092): 	at java.lang.Thread.run(Thread.java:864)
,I/SensorManager(  906): mEventCount = 450
,E/SQLiteDatabase( 4092): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4092): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4092): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4092): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4092): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4092): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4092): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4092): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4092): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4092): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4092): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4092): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4092): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4092): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4092): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4092): 	at java.lang.Thread.run(Thread.java:864)
W/GAV2    ( 4092): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/DeviceManagement( 4079): WorkflowService: Starting workflow service
I/DeviceManagement( 4079): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b110a8] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 4079): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 4079): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4079): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4079): SessionStateController: Checking invariants...
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4034): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4034): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4034): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,E/SharedPreferencesImpl( 4034): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
,D/Process (  906): killProcessQuiet, pid=3592
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3592:com.htc.task/u0a70 (adj 15): empty #17
,E/SQLiteDatabase( 4079): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4079): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4079): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4079): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4079): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4079): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4079): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4079): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4079): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4079): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4079): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4079): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4079): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4079): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4079): SessionStateController: Checking invariants...
,E/SQLiteDatabase( 4079): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4079): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4079): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4079): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4079): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4079): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4079): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4079): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4079): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfig(ConfigManagerController.java:126)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow.doServiceMethod(ConfigManagerServiceGetConfigWorkflow.java:44)
E/SQLiteDatabase( 4079): 	at com.htc.cs.dm.config.service.ConfigManagerServiceWorkflow.invokeServiceMethod(ConfigManagerServiceWorkflow.java:50)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.service.ServiceWorkflow.call(ServiceWorkflow.java:44)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4079): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4079): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentServic,e.java:65)
E/SQLiteDatabase( 4079): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4079): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4079): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DeviceManagement( 4079): ServiceWorkflow: Uncaught throwable
E/DeviceManagement( 4079): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/DeviceManagement( 4079): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/DeviceManagement( 4079): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/DeviceManagement( 4079): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/DeviceManagement( 4079): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/DeviceManagement( 4079): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/DeviceManagement( 4079): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/DeviceManagement( 4079): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfig(ConfigManagerController.java:126)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow.doServiceMethod(ConfigManagerServiceGetConfigWorkflow.java:44)
E/DeviceManagement( 4079): 	at com.htc.cs.dm.config.service.ConfigManagerServiceWorkflow.invokeServiceMethod(ConfigManagerServiceWorkflow.java:50)
E/DeviceManagement( 4079): 	at com.htc.cs.util.service.ServiceWorkflow.call(ServiceWorkflow.java:44)
E/DeviceManagement( 4079): 	at com.htc.cs.util.w,orkflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/DeviceManagement( 4079): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/DeviceManagement( 4079): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DeviceManagement( 4079): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DeviceManagement( 4079): 	at android.os.Looper.loop(Looper.java:157)
E/DeviceManagement( 4079): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DeviceManagement( 4079): ServiceWorkflow: android.database.sqlite.SQLiteException: message=[not an error (code 0): Could not open the database in read/write mode.]
I/DeviceManagement( 4079): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b110a8]
I/DeviceManagement( 4079): WorkflowService: Stopping workflow service
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4146 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  906): killProcessQuiet, pid=3712
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/htcbackup-core( 4114): ModelAsyncTask: Caught exception running async model handler: java.lang.IllegalStateException: android.database.sqlite.SQLiteException: message=[not an error (code 0): Could not open the database in read/write mode.]
I/ActivityManager(  906): Killing 3712:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3712
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcCupdReceiver(Provider)( 4146):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  906): Recipient 3592
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(427980f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3781 10160 null
,I/Prism.ItemManager( 3885): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3885): loadItems() com.htc.launcher.pageview.WidgetManager@41b45c68 +
,I/Prism.WidgetManager( 3885): onLoadItems() +
D/PMS     (  906): releaseWL(427980f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=-2s43ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(427aac30): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/Process (  906): killProcessQuiet, pid=3923
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Killing 3923:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  906): Recipient 3923
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onDataStallAlarm: ignore, tag=19940 expecting 19941
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
,V/AlarmManager(  906): sending alarm PendingIntent{41dd82f0: PendingIntentRecord{424907d0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58477, Int=0
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b66dd0 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,E/SharedPreferencesImpl( 2611): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/PlayLogUploaderPrefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/PlayLogUploaderPrefs.xml.bak
V/AlarmManager(  906): sending alarm PendingIntent{42421b08: PendingIntentRecord{4265a128 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1449275252944, Int=0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/DirectoryFileManager( 2611): Could not ensure directory exists.
,E/SharedPreferencesImpl( 2611): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml to backup file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml.bak
,E/LogStore( 2611): Could not write string (a: 1449275252936
E/LogStore( 2611): b: "system_health"
E/LogStore( 2611): c: 0
E/LogStore( 2611): d: 0
E/LogStore( 2611): e: false
E/LogStore( 2611): h: "\012\37777777606\001\012\0245.0.89 (1307510-038)\020\37777777766\37777777746O\030\005 \003(\0102d\012\0051.6.0\022\023The Android Project\032\006Dalvik\"\0030.9*\023The Android Project2$Dalvik Virtual Machine Specification\022\012\010\001\020\001\032\004@\001H\003"
E/LogStore( 2611): i: ""
E/LogStore( 2611): j: ""
E/LogStore( 2611): l: ""
E/LogStore( 2611): ) to file: Directory doesn't exist.
E/LogStore( 2611): java.io.IOException: Directory doesn't exist.
E/LogStore( 2611): 	at hrv.a(SourceFile:372)
E/LogStore( 2611): 	at hsa.a(SourceFile:322)
E/LogStore( 2611): 	at hsa.a(SourceFile:345)
E/LogStore( 2611): 	at hrt.a(SourceFile:138)
E/LogStore( 2611): 	at hrt.a(SourceFile:148)
E/LogStore( 2611): 	at hrs.k(SourceFile:247)
E/LogStore( 2611): 	at hrs.a(SourceFile:126)
E/LogStore( 2611): 	at hrq.a_(SourceFile:40)
E/LogStore( 2611): 	at bur.b(SourceFile:296)
E/LogStore( 2611): 	at bux.a(SourceFile:188)
E/LogStore( 2611): 	at buw.a(SourceFile:561)
E/LogStore( 2611): 	at buq.d(SourceFile:192)
E/LogStore( 2611): 	at bup.handleMessage(SourceFile:128)
E/LogStore( 2611): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/LogStore( 2611): 	at android.os.Looper.loop(Looper.java:157)
E/LogStore( 2611): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/LogStore( 2611): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/LogStore( 2611): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/LogStore( 2611): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/LogStore( 2611): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/LogStore( 2611): 	at dalvik.system.NativeStart.main(Native Method)
,E/PlayLogBrokerService( 2611): --> failed to write
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2611/10028)
,E/SharedPreferencesImpl( 2611): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml to backup file /data/data/com.google.android.gms/shared_prefs/DownloadService.xml.bak
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/AdsMeasurementBroadcastReceiver( 2611): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2611): Unauthorized to start the main service
V/AlarmManager(  906): sending alarm PendingIntent{4240f1a0: PendingIntentRecord{42685c98 com.google.android.gms startService}}, i=null, t=0, cnt=17066, w=84918423, Int=84918423
,D/Settings:HtcWirelessFeatureFlags( 3948): id/is att sku: 99/false
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4169 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/SystemReader( 3948): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3948): Cannot find support_harman, use default value instead
,W/SystemReader( 3948): Cannot find effect_manager_id, use default value instead

```
