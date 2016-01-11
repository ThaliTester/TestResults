#### Test 55613145e2b298d_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  915): acquireWL(41ff37c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{41f62ed8: PendingIntentRecord{42780b68 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=96191, Int=0
D/PMS     (  915): acquireWL(439d34b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 915 1000 null
D/PMS     (  915): releaseWL(41ff37c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): acquireWL(42801640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(439d34b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  915): releaseWL(42801640): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  915): Waited long enough for: ServiceRecord{42d3abf0 u0 com.htc.htclocationservice/.AutoSettingService}
--------- beginning of /dev/log/main
E/cutils-trace( 4542): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4542): ====startRecUseTime====
D/htc.customization.log.level( 4542):  is 
W/CustomizationLogLevel( 4542): Level value is invalid, use default level 2
D/CustomizationManager( 4542):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4542): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4542): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4542): Parsing tag category name = system
I/CustomizationCIDLoader( 4542): Parsing tag category name = application
I/CustomizationCIDLoader( 4542): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4542): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4542): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4542): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4542): Parsing tag category name = Settings
D/CustomizationManager( 4542):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4542):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 4542): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4542): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4542): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4542): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  915): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  915): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  915): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4542
D/PMS     (  915): acquireHCC(4275a7a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 915 1000 null
D/PMS     (  915): acquireHCC(41e64148): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 915 1000 null
W/asset   (  915): Copying FileAsset 0x62ae0a58 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  915): @test_code: getHtcIntentFlag: 0 obj: 1116324104
I/FeedHostManager( 1278): [onPause]
I/FeedProviderManager( 1278): onPause
I/FeedHostManager( 1278): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4232c160
I/SocialFeedProvider( 1278): +onPause
I/SocialFeedProvider( 1278): -onPause
D/PMS     (  915): acquireWL(426c7190): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 915 1000 null
I/ActivityManager(  915): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4553 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1278): [trimMemory] 20
W/asset   ( 4553): Copying FileAsset 0x5c6f5630 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4553): Binding Chromium to main looper Looper (main, tid 1) {41d87de0}
I/LibraryLoader( 4553): Expected native library version number "",actual native library version number ""
I/chromium( 4553): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4553): Initializing chromium process, renderers=0
D/PMS     (  915): acquireWL(43a7c190): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  915): java.lang.Throwable: stack dump
D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4383acf8:true
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4553): 1104796752: getState(). Returning 12
D/PMS     (  915): acquireWL(4289bfe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  915): releaseWL(43a7c190): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4553): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4553): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4553): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4553): Local Branch: 
I/Adreno-EGL( 4553): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4553): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4553):                  aa63bbd948f41d15fc72f585e
W/chromium( 4553): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4553): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4553): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4553): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4553): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4553): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4553): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4553): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4553): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4553): CordovaWebView is running on device made by: HTC
,W/AwContents( 4553): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  915): Disable input method client, pid=1278
,W/ResourceType( 4553): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4553): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41dcf300, mServedView=org.apache.cordova.engine.SystemWebView{41d94f68 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1214): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1214): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1214): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1214): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  915): Displayed com.test.thalitest/.MainActivity: +289ms
,I/InputMethodManagerService(  915): Enable input method client, pid=4553
W/AwContents( 4553): nativeOnDraw failed; clearing to background color.
,D/PMS     (  915): releaseWL(426c7190): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4553): Set native->JS mode to OnlineEventsBridgeMode
,V/LightsService(  915): setLight #0: color=#26
,V/LightsService(  915): setLight #0: color=#23
,V/LightsService(  915): setLight #0: color=#1c
,D/jxcore_app_log( 4553): JniHelper::setJavaVM(0x41946010), pthread_self() = 1662757440
,D/JX-Cordova( 4553): jxcore cordova android initializing
,V/LightsService(  915): setLight #0: color=#15
,V/LightsService(  915): setLight #0: color=#14
,D/Process (  915): killProcessQuiet, pid=4174
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4174:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4174
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 11.613MB for 96598-byte allocation
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 11.695MB for 144892-byte allocation
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 11.811MB for 217334-byte allocation
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 11.983MB for 325996-byte allocation
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  915):    returned true
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 12.245MB for 488990-byte allocation
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 13.262MB for 1100216-byte allocation
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 14.167MB for 1650320-byte allocation
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 15.515MB for 2475476-byte allocation
,W/CpuWake (  915): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  915): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  915): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  915): releaseHCC(4275a7a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/CpuWake (  915): >>release mCpuPerf_Freq wakelock
W/CpuWake (  915): <<release mCpuPerf_Freq wakelock
,D/PMS     (  915): releaseHCC(41e64148): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4553): Grow heap (frag case) to 17.577MB for 3713210-byte allocation
,I/SensorManager(  915): mEventCount = 1200
,W/jxcore-log( 4553): Initializing JXcore engine
,W/jxcore-log( 4553): JXcore engine is ready
,W/jxcore-log( 4553): Starting JXcore engine
,W/jxcore-log( 4553): Platform android
W/jxcore-log( 4553): 
,W/jxcore-log( 4553): Process ARCH arm
W/jxcore-log( 4553): 
,D/PMS     (  915): releaseWL(4289bfe0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4553): JXcore Cordova bridge is ready!
I/jxcore-log( 4553): 
,W/jxcore-log( 4553): JXcore engine is started
,I/chromium( 4553): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  915): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4599 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/dalvikvm-heap( 1278): Grow heap (frag case) to 13.315MB for 53840-byte allocation
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1278): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Launcher( 1278): Deferring update until onResume
,D/Launcher( 1278): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  915):    returned true
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,E/ExternalAccountType( 1347): Unsupported attribute readOnly
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4599): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4599): MmsConfig.loadMmsSettings
,W/dalvikvm( 4599): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4599): VFY: unable to resolve instance field 36
,W/dalvikvm( 4599): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4599): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  915): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4622 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4599, uid=10111, userID:0
,W/Settings( 4599): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4599, uid=10111, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4599, uid=10111, userID:0
,D/MessageFrequencyProvider( 4622): onCreate
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4599, uid=10111, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4599, uid=10111, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4599, uid=10111, userID:0
D/PMS     (  915): acquireWL(43638e38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4599 10111 null
,V/GetPrviateResource( 4622): GetPrviateResource
,V/GetPrviateResource( 4622): GetPrviateResource
,D/MmsCustomizationProvider( 4622): query uri: content://htc-mms-customization/mms-ua/ua_string
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  915): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  915): acquireWL(42baeb70): PARTIAL_WAKE_LOCK  AsyncService 0x1 3552 10160 null
,D/MmsCustomizationProvider( 4622): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/PMS     (  915): releaseWL(42baeb70): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  915): Resuming delayed broadcast
I/ActivityManager(  915): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
I/Babel   ( 4599): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4599): MmsConfig.loadFromDatabase
,D/Process (  915): killProcessQuiet, pid=4339
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/PMS     (  915): acquireWL(428ea990): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  915): Killing 4339:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/PMS     (  915): releaseWL(428ea990): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/Babel   ( 4599): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4599): MmsConfig.loadFromResources
,E/Babel   ( 4599): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4599): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  915): Resuming delayed broadcast
I/ActivityManager(  915): Recipient 4339
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  915): acquireWL(43b5ac70): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43638e38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  915): Resuming delayed broadcast
,D/Process (  915): killProcessQuiet, pid=4362
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  915): Killing 4362:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  915): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 4362
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2178): Null package name or gms related package.  Ignoreing.
,D/MessageCustFlag( 4622): sense_version=6.0
,D/BTAccessoryUtil( 4622): createReceiver
,D/BTAccessoryUtil( 4622): registerReceiver return intent = null
D/MessageCustFlag( 4622): sku_id=99
,W/SystemReader( 4622): Cannot find message_ambs_application_id, use default value instead
,I/ProviderInstaller( 4599): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  915): Resuming delayed broadcast
D/Messaging( 4622): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4622): networkCode: 
D/MessageCustFlag( 4622): sku_id=99
D/MmsConfig( 4622): SIE smsPri: null
D/MmsConfig( 4622): networkCode: 
,D/HtcTelephonyCapability( 4622): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4622): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4622): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4622): Cannot find qct_8960_interface, use default value instead
,I/Icing   ( 2178): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  915): Unable to load service info ResolveInfo{429c84b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  915): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  915): start
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 385 ms] updated apps [took 385 ms] 
,I/GCoreNlp( 1229): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  915): applying state to connected service
,D/PMS     (  915): acquireWL(43462dd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  915): applying state to connected service
D/PMS     (  915): releaseWL(43462dd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43adbc00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(42946ed8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43adbc00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42946ed8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(442ce390): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(442ce390): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 4553): Toggling radios to true
I/jxcore-log( 4553): 
,D/BluetoothAdapter( 4553): enable(): BT is already enabled..!
,D/WifiManager( 4553): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  915): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  915): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  915): Settings:Agentvalue: 2
W/Settings:Agent(  915): >> traceCallingStack()
W/Settings:Agent(  915): Process.myPid(): 915
W/Settings:Agent(  915): Process.myTid(): 1376
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
W/System.err(  915): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  915): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  915): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  915): 
,W/Settings:Agent(  915): << traceCallingStack(): 1(ms)
D/WifiManager( 4553): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  915): doBoolean: DISCONNECT
,D/WifiManager( 4553): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): TDLS: Tear down peers
,I/wpa_supplicant( 1165): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4553): Radios toggled
I/jxcore-log( 4553): 
,D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  915): New client listening to asynchronous messages
D/WifiService(  915): setWifiEnabled: true pid=4553, uid=10389
E/WifiService(  915): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  915): isSprintWifiRestricted(): false
I/WifiService(  915): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  915): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/BluetoothManagerService(  915): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4553): Received device characteristics:
I/jxcore-log( 4553): Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4553): Bluetooth name: HTC Desire 820
I/jxcore-log( 4553): Device name: HTC-HTC Desire 820
I/jxcore-log( 4553): 
I/jxcore-log( 4553): Perf Test app loaded loaded
I/jxcore-log( 4553): 
I/jxcore-log( 4553): check test folder
I/jxcore-log( 4553): 
I/jxcore-log( 4553): found test : ./testFindPeers.js
I/jxcore-log( 4553): 
,I/jxcore-log( 4553): found test : ./testSendData.js
I/jxcore-log( 4553): 
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1165): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1165): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,D/HTCRequest(  915): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  915): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  915): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1165): TDLS: Remove peers on disassociation
D/HTCRequest(  915): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  915): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/WifiMonitor(  915): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/Tethering(  915): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb87e7bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1165):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1165): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd, 18
I/wpa_supplicant( 1165): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1165): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  915):    returned true
D/WifiPerfLock(  915): release()
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
D/Tethering(  915): interfaceStatusChanged wlan0, false
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  915): PerfLock released for exiting ConnectedState
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  915):    returned true
,D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  915): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  915): acquireWL(42e35988): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 915 1000 null
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  915): doBoolean: RECONNECT
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): Fast associate: Old scan results
I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
D/WifiNative-wlan0(  915):    returned true
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  915): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  915): stopDataStallAlarm: current tag=19784 mDataStallAlarmIntent=PendingIntent{438c1060: PendingIntentRecord{42710990 android broadcastIntent}}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
D/WIFI_ICON( 1122): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSID
,I/IntentController( 1122): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/DhcpStateMachine(  915): [RunningState] Stop DHCP
D/WifiP2pService(  915): InactiveState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  915): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  915): Provision feature enable=false
D/ConnectivityService(  915): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/UsbnetStateTracker(  915): isAvailable+-
D/UsbnetStateTracker(  915): reconnect
D/UsbnetStateTracker(  915): isAvailable+-
,D/WISPrService( 3792): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  915): Exit handleNetworkDisconnect
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1122): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3792): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  915): default: reconnect()
D/MDST    (  915): default: setTeardownRequested(false)
D/MDST    (  915): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  915): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  915): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  915): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  915): New client listening to asynchronous messages
W/ConnectivityService(  915): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  915): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  915): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  915): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 1378): Read error: ssl=0x63f6f740: I/O error during system call, Connection timed out
,D/WISPrService( 3792): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  915): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  915): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  915): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  915): handleConnectivityChange: resetting
,D/ConnectivityService(  915): resetConnections(wlan0, 3)
D/WifiStateMachine(  915): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3792): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] entry_id:3   entry:0xb883a220  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8839d90  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8839fd8  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb883a2f8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb883a428  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb883a860  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb883a0e8  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb8839f10  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/ConnectivityService(  915): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  915): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  915): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  915): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  915): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/WIFI_ICON( 1122): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
D/WirelessDisplayService(  915): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  915): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/QuickSettingWifi( 1122): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiStateMachine(  915): startScan Pid: 915 Uid 1000
,D/WifiNative-wlan0(  915): doBoolean: SCAN
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1165): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  915):    returned false
D/BatSI   (  915): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  915): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1122): receive.wifiConnect:false wifiAPname:null elapse:0
,I/Choreographer( 4553): Skipped 110 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4553): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  915): acquireWL(42d46d70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,V/NativeCrypto( 1378): SSL shutdown failed: ssl=0x63f6f740: I/O error during system call, Broken pipe
D/PMS     (  915): acquireWL(4445da58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 915 1000 null
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): reportInetCondition for net -1, percentage: 0 by  (1378/10029)
,D/ConnectivityService(  915): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/PMS     (  915): releaseWL(42d46d70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/PMS     (  915): releaseWL(4445da58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/Icing   ( 2178): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e1ce18 +
,I/Prism.WidgetManager( 1278): onLoadItems() +
,I/Icing   ( 2178): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  915): releaseWL(43b5ac70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  915): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  915): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4663 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Tethering(  915): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  915): bSetPropertyMultiRAB:false
,D/Tethering(  915): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  915): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  915): ipv4Default null
I/Tethering(  915): No IPv4 upstream interface, giving up.
,D/Tethering(  915): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
D/CaptivePortalTracker(  915): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  915): NoActiveNetworkState
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
,I/ConnectivityHelper( 1278): [onReceive] WIFI(1): DISCONNECTED
D/GpsLocationProvider(  915): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  915): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  915): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  915): ignore wifi update if we are not in OPENING or CLOSING
,D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
E/Prism.WidgetManager( 1278): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1278): onLoadItems() -
,I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e1ce18 -
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.htc.launcher (1278/10076)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/PMS     (  915): acquireWL(432d7c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 915 1000 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1629/10029)
D/PMS     (  915): releaseWL(432d7c50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,I/MusicStore( 4663): Database version: 95
,W/ContextImpl( 4663): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4663): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4663): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4663): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4663): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4663, uid=10154, userID:0
,D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
,D/MediaRouterService(  915): Client com.google.android.music (pid 4663): Registered
,D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
I/MediaRouter( 4663): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.music (4663/10154)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1937/10021)
D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1245): -- N1 =0
D/PhoneApp( 1245): -- N2 =0
D/PhoneApp( 1245): -- N3 =0
,I/ActivityManager(  915): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4683 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4663): getSelectedRoute
,D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.google.android.music (4663/10154)
I/NetworkMonitor( 4663): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4663, uid=10154, userID:0
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): acquireWL(43abb200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/ACRA    ( 4683): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  915): killProcessQuiet, pid=4326
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  915): releaseWL(43abb200): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  915): Killing 4326:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/ACRA    ( 4683): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4683): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 4326
,W/SystemClassLoaderAdder( 4683): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4683): Preparing secondary program dexes.
V/DexLibLoader( 4683): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4683): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4683): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4683): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4683): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4683): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4683): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4683): Dex already copied
D/OdexVerifier( 4683): Odex verification is skipped.
,V/DexLibLoader( 4683): Creating class loader
,V/DexLibLoader( 4683): Finished creating class loader
V/DexLibLoader( 4683): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4683): Dex already copied
D/OdexVerifier( 4683): Odex verification is skipped.
,V/DexLibLoader( 4683): Creating class loader
,V/DexLibLoader( 4683): Finished creating class loader
V/DexLibLoader( 4683): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4683): Dex already copied
D/OdexVerifier( 4683): Odex verification is skipped.
,V/DexLibLoader( 4683): Creating class loader
,V/DexLibLoader( 4683): Finished creating class loader
V/DexLibLoader( 4683): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4683): Dex already copied
D/OdexVerifier( 4683): Odex verification is skipped.
,V/DexLibLoader( 4683): Creating class loader
,V/DexLibLoader( 4683): Finished creating class loader
,V/DexLibLoader( 4683): Verifying classes from secondary dexes.
,D/DexLibLoader( 4683): DexLibLoader.ensureDexLoaded took 24 ms
,D/Messaging( 4622): mNeedToUpdateDate2 start
,D/MmsConfig( 4622): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4622): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4622): 
D/MmsAsyncWorkHandler( 4622): HM tk = 20001
D/ReportIndicatorCache( 4622): MSG_QUERY_REPORTS >>
D/SettingsManager( 4622): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41d932e8
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
I/Messaging( 4622): mccmnc> 
,D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4622): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4622): [DraftCache/1] refresh
,D/MmsConfig( 4622): networkCode: 
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4622): ViewCache CreatePreloadOnlyConversationList
,D/Messaging( 4622): mNeedToUpdateDate2: false
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1245):  phoneType = -1
D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4622): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4622): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4622): createReceiver
,D/MessageCustFlag( 4622): sense_version=6.0
,D/Jerry   ( 4622): start to preload cursor >>>>>>>
,D/TelephUtils( 1245): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1245): Update uri=content://mms, match=0
,V/MmsProvider( 1245): selection=st=129 AND m_type!=134
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Messaging( 4622): Reset downloading state: 0
V/MmsSystemEventReceiver( 4622): TransactionService is going to be woken up.
,D/AccFlag ( 1245): sku_id=99
,V/TransactionService( 4622): 1-Creating TransactionService
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/DraftCache( 4622): [DraftCache/454] rebuildCache
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4622): ViewCache CreatePreload
,D/Messaging( 4622): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4622): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,V/TransactionService( 4622): onStartCommand: 1
,D/MmsSystemEventReceiver( 4622): unRegisterForConnectionStateChanges
V/TransactionService( 4622): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4622): Loading previous transactions.
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/Jerry   ( 1245): URI_DRAFT
,D/Cust_MMSMS( 4622): _has_set_default_values_2=true
,D/DraftCache( 4622): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4622): [DraftCache/454] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4622): 
D/MmsAsyncWorkHandler( 4622): HM tk = 20002
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1245): device_type: 1
,D/MsgPreferenceUtils( 4622): def_index: 0
D/TransactionService( 4622): Force set service start id to 1
V/TransactionService( 4622): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4622): unRegisterForConnectionStateChanges
D/TransactionService( 4622): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4622): Destroying TransactionService
D/MsgPreferenceUtils( 4622): globalIndex = 1
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1245): sku_id=99
D/MsgPreferenceUtils( 4622): phone state: true
D/MsgPreferenceUtils( 4622): sd state: false
,D/MsgPreferenceUtils( 4622): vIndex = 0
,V/TransactionService( 4622): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1245): sku_id=99
,W/dalvikvm( 4683): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4683): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4683): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4683): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4683): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4683): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4683): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-81
D/wpa_supplicant( 1165): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1165): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1165): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1165): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 3
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 1
I/wpa_supplicant( 1165): wpa_s->is_screen_on 1
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): selected network = 1
D/wpa_supplicant( 1165): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb87e94e8  current_ssid=0x0
D/wpa_supplicant( 1165): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1165): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1165): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1165): check if in concurrent case
I/wpa_supplicant( 1165): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  915): doString: LIST_DONGLES
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1165): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1165): RSN: PMKSA cache search - network_ctx=0xb87e94e8 try_opportunistic=0
D/wpa_supplicant( 1165): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1165): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1165): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1165): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1165): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1165): nl80211: Unsubscribe mgmt frames handle 0xb87e8718 (mode change)
D/wpa_supplicant( 1165): nl80211: Subscribe to mgmt frames with non-AP handle 0xb87e8718
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Register frame type=0xd0 nl_handle=0xb87e8718
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1165): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1165):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1165):   * freq=2412
D/wpa_supplicant( 1165):   * Auth Type 0
D/wpa_supplicant( 1165):   * WPA Versions 0x2
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1165): nl80211: Connect request send successfully
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  915): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (489) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000104140987
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000104141003
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2452
I/wpa_supplicant( 1165): level=-81
I/wpa_supplicant( 1165): tsf=0000000104141015
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000104140999
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  915): getDiscoveryDongleList
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  915): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 104140987, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/WifiStateMachine(  915): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 104141003, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2452, timestamp: 104141015, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 104140999, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): add 4 to mScanResults
D/BatSI   (  915): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  915): == begin of scan result ==
,D/WifiStateMachine(  915): == (4) end of scan result ==
,D/WifiManager( 1229): getScanResults enter 
D/WirelessDisplayService(  915): getDiscoveryDongleList
D/WifiStateMachine(  915): == begin of scan result ==
,D/WifiStateMachine(  915): == (4) end of scan result ==
D/WifiNotificationController(  915): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1165): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
D/Tethering(  915): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1165): nl80211: Event message available
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1165): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1165): nl80211: Connect event
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1165): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1165): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1165): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1165): TDLS: Remove peers on association
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1165): EAPOL: enable timer tick
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
D/Tethering(  915): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/Tethering(  915): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1165): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1165): Get randomness: len=32 entropy=5
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700,
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  915): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  915): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  915): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  915): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  915): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  915): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  915): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/WifiStateMachine(  915): Enter handleAssociatedWithEvent
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  915): Associated
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  915): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  915): Exit handleAssociatedWithEvent
D/WifiStateMachine(  915): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  915): updateConnectedAP...
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
,D/WifiStateMachine(  915): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  915): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  915): This record is existed, only update it...
D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
,I/wpa_supplicant( 1165): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb87e89f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1165):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1165): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0db4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1165):    broadcast key
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1165): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1165): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1165): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1165): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1165): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  915): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1165): set send_ind_to_ndc = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1165): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 1165): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/Tethering(  915): interfaceLinkStateChanged wlan0, true
D/Tethering(  915): interfaceStatusChanged wlan0, true
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state IDLE
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1165): EAPOL authentication completed successfully
I/wpa_supplicant( 1165): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1165): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1165): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1165): nl80211: if_removed already cleared - ignore event
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  915): updateConnectedAP...,
,D/WifiStateMachine(  915): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  915): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  915): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  915): This record is existed, only update it...
D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
,I/IntentController( 1122): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3792): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  915): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  915): Provision feature enable=false
D/ConnectivityService(  915): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1122): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3792): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  915): updateConnectedAP...
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
,D/DhcpStateMachine(  915): [StoppedState] Start DHCP
D/WifiStateMachine(  915): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
,D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
,D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 1
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  915):    returned true
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
D/WifiStateMachine(  915): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  915): acquireWL(43f83b20): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 915 1000 null
,D/WifiStateMachine(  915): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  915): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  915):    returned null
E/WifiStateMachine(  915): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  915): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  915):    returned null,
D/WifiP2pService(  915): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426d33c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@426d33c0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1122): receive.wifiConnect:false wifiAPname:null elapse:1
,W/dalvikvm( 4683): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4683): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/PMS     (  915): Going to sleep due to screen timeout...
,I/ActivityManager(  915): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,I/SensorManager(  915): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4249d968
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  915): disable: get sensor name = CM36282 Light sensor
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 2
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4249d968, eanble = 0, strlen(mName) = 59
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  915): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4240e360
W/SensorService(  915): Listener[1] = com.htc.smartdim.sensor_eye@428d6450
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  915): setLight #2: color=#0
D/qdlights(  915): set_light_buttons_func: on=0 brightness=0
V/LightsService(  915): setLight #0: color=#0
,D/WirelessDisplayService(  915): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  915): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  915): mWirelessDisplayManager is null
,E/FbInjectorInitializer( 4683): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4683): Verify
,D/SurfaceControl(  915): Excessive delay in blankDisplay() while turning screen off: 317ms
D/PMS     (  915): nativeSetInteractive:false
D/PMS     (  915): nativeSetInteractive:false done
D/PMS     (  915): nativeSetAutoSuspend:true
D/PMS     (  915): nativeSetAutoSuspend:true done
D/NfcService( 1262): ScreenObserver: OFF
,D/NfcService( 1262): applyRouting - 0
,I/IntentController( 1122): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/HABCtrl (  915): TPE algorithm. remove timeout.
D/PMS     (  915): OOBE c monitor 11
I/InputManager(  915): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  915): screenObserver, isScreenOn=false
I/InputMethodManagerService(  915): Disable input method client, pid=4553
D/PMS     (  915): acquireWL(432adb28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
V/KeyguardServiceDelegate(  915): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43293030)
,D/NfcService( 1262): applyRouting -2
,V/KeyguardServiceDelegate(  915): **** SHOWN CALLED ****
D/PMN     (  915): wakingUp
D/PMS     (  915): releaseWL(432adb28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  915): No lock screen! windowToken=null
W/ResourceType( 4553): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4553): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41d94f68 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMN     (  915): onScreenOn
D/WifiService(  915): New client listening to asynchronous messages
D/PMS     (  915): acquireWL(43e73e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
D/WirelessDisplayService(  915): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  915): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  915): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(43e73e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
D/AlarmManager(  915): ACTION_SCREEN_ON
I/AlarmManager(  915): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  915): [AlarmQueuing] done recovering
I/AlarmManager(  915): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  915): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 1937): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1262): applyRouting - 0
,D/MtpService( 1937): [MTP][onReceive]-
,I/ClockThread( 1122): stop update clock
,D/NfcService( 1262): applyRouting -2
D/PMS     (  915): acquireWL(4293a2e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1262 1027 null
D/WirelessDisplayService(  915): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  915): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  915): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  915): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  915): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:On
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  915):    returned true
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0],
I/wpa_supplicant( 1165): Change stage from stage0 to stage3
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
V/NotificationService(  915): batLight: Full, plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c800,
D/qdlights(  915): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  915): releaseWL(4293a2e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  915): batLight: Full, plugged,
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c800
D/qdlights(  915): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7,
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144,
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
V/SRS_Proc(  372): ParamSet string: screen_state=on
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  915):    returned true,
,D/WirelessDisplayService(  915): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
D/NetworkPolicy(  915): updateScreenOn: false
,W/fb4a(:<default>):BaseAnalyticsConfig( 4683): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4683): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43ae5ad0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  915): releaseWL(43ae5ad0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(4437e1d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOn: 1452523210030
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOn: 1452523210030
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/PMS     (  915): releaseWL(4437e1d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SensorManager(  915): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4240e360
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 2
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4240e360, eanble = 0, strlen(mName) = 91
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  915): Listener[0] = com.htc.smartdim.sensor_eye@428d6450
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  915): goingToSleep
D/PMS     (  915): acquireWL(43f728f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 915 1000 null
,D/Process (  915): killProcessQuiet, pid=4380
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  915): Killing 4380:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4380
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): releaseWL(43f728f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  915): ACTION_SCREEN_OFF
I/AlarmManager(  915): [AlarmQueuing] screen off now: 
I/AlarmManager(  915): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  915): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  915): stopDataStallAlarm: current tag=19785 mDataStallAlarmIntent=null
I/AlarmManager(  915): [AlarmQueuing] wifi connection: true
D/WifiNative-wlan0(  915): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:Off
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1165): get_ip_address source addr = 02000000
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  915):    returned true
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  915): acquireWL(4439f6a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 915 1000 null
D/PMS     (  915): releaseWL(4439f6a0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/ActivityManager(  915): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4743 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): Util - no network available!
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/AutoSetting( 1320): service - onCreate()
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/NetworkPolicy(  915): updateScreenOn: false
D/AutoSetting( 1320): service - AddressCache: using context: com.htc.Weather
D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
D/ContactMessageStore( 1245): Background delete complete
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  915): request 426ad9d8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  915): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1320): service - mHandler: cancel location update
D/AutoSetting( 1320): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4683): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4683): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4683): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4743): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4743): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4743): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4743): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  915): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4760 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4743/10079)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4743/10079)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4743/10079)
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] getTotalRam: 1873 Mb
D/PMS     (  915): acquireWL(43b5b2f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43b5b2f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(443a8140): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1777): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1777): disableBatteryAlarm: null
,D/PMS     (  915): releaseWL(443a8140): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1777): onScreenOff
,I/ActivityManager(  915): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4775 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  915): killProcessQuiet, pid=4252
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Killing 4252:com.htc.mediamanager/u0a34 (adj 15): empty #17
,E/dalvikvm( 4683): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4683): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4683): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4683): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4683): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4683): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4683): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4683): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4683): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4683): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4683): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4683): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4683): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4683): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4683): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4683): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4683): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/wpa_supplicant( 1165): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1165): EAPOL: disable timer tick
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4775): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 9.923MB for 39954-byte allocation
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4775): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4775): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4775): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4775): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 9.997MB for 79892-byte allocation
I/ActivityManager(  915): Recipient 4252
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 10.070MB for 84664-byte allocation
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 10.097MB for 28144-byte allocation
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4775/10151)
,V/WebViewChromiumFactoryProvider( 4775): Binding Chromium to main looper Looper (main, tid 1) {41d8eec8}
,I/LibraryLoader( 4775): Expected native library version number "",actual native library version number ""
,I/chromium( 4775): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4775): Initializing chromium process, renderers=0
,D/PMS     (  915): acquireWL(43198638): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4775): BLUETOOTH permission is missing!
D/PMS     (  915): acquireWL(431ddbd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  915): releaseWL(431ddbd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4775): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4775): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4775): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4775): Local Branch: 
I/Adreno-EGL( 4775): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4775): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4775):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4775): Starting up...
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4775/10151)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4775/10151)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (3552/10160)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (3552/10160)
,D/Process (  915): killProcessQuiet, pid=4425
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  915): Killing 4425:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4425
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,I/iu.Environment( 2178): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2178): num queued entries: 0
,I/iu.UploadsManager( 2178): num updated entries: 0
,I/iu.SyncManager( 2178): NEXT; no task
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,I/dalvikvm-heap( 4683): Grow heap (frag case) to 10.285MB for 75760-byte allocation
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{434af2e0 u0 ReceiverList{434af1c0 4683 com.facebook.katana/10027/u0 remote:428a7818}}
W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{434af2e0 u0 ReceiverList{434af1c0 4683 com.facebook.katana/10027/u0 remote:428a7818}}
W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{443b6e40 u0 ReceiverList{443b6de0 4683 com.facebook.katana/10027/u0 remote:442f6f90}}
,I/ActivityManager(  915): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4813 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,W/ContextImpl( 4813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4813): isEpsOn(), nState = 0
D/PMS     (  915): acquireWL(42947ab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4813 1000 null
,D/PMS     (  915): releaseWL(42947ab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  915): acquireWL(43d8e838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  915): releaseWL(43d8e838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3792): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3792): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3792): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3792): Cust_ConnectToPC   : spcsc>false
D/        ( 3792): Cust_ConnectToPC   : IPT>true
,D/        ( 3792): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3792): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3792): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3792): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3792): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3792): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3792): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3792): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3792): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3792):  defaultType:0
I/ActivityManager(  915): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  915): Resuming delayed broadcast
,D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/SmartSyncUtils( 4813): isEpsOn(), nState = 0
W/ContextImpl( 4813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4683): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/SensorManager(  915): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@428d6450
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  915): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 1
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@428d6450, eanble = 0, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 0
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@428d6450, eanble = 0, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  915): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@428d6450
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4683): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
E/ActivityThread(  915): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428e1310 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  915): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@428e1310 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  915): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  915): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  915): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  915): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  915): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  915): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  915): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  915): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  915): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  915): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  915): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  915): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  915): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  915): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  915): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  915): 	at dalvik.system.NativeStart.main(Native Method)
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4683): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/SmartSyncUtils( 4813): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4813): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4813): getMobilePolicyEnabled, result = true
D/WifiService(  915): New client listening to asynchronous messages
,D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  915): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,D/Process (  915): killProcessQuiet, pid=4439
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4439:com.htc.calendar/u0a13 (adj 15): empty #17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
,D/WifiStateMachine(  915): handlePostDhcpSetup release wake lock during DHCP
I/ActivityManager(  915): Recipient 4439
D/WifiP2pService(  915): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): releaseWL(43f83b20): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
,D/WifiStateMachine(  915): gateway: /192.168.1.1
D/WifiNative-wlan0(  915): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  915):    returned true
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  915): VerifyingLinkState enter
D/WifiStateMachine(  915): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  915): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  915): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1122): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1122): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  915): WAN detection
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  915): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  915): Provision feature enable=false
V/NetworkPolicy(  915): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  915): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  915): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  915): default: teardown()
D/MDST    (  915): default: setTeardownRequested(true)
D/MDST    (  915): default: setEnableApn apnType =default , enable=false
D/MDST    (  915): default: setTeardownRequested(true)
D/ConnectivityService(  915): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 3792): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/ConnectivityService(  915): Unexpected mtu value: android.net.wifi.WifiStateTracker@42710130
D/ConnectivityService(  915): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  915): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  915): syncGetConfiguredNetworks
D/WIFI_ICON( 1122): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  915): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  915): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  915): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  915): handleConnectivityChange: resetting
D/Nat464Xlat(  915): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  915): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  915): sendGeneralBroadcastDelayed, restrictEnable=false
,I/QuickSettingWifi( 1122): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  915): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  915):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  915): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  915): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  915): acquireWL(43f87b18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 915 1000 null
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4743/10079)
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  915): acquireWL(43efbfe0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43edde08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452523199040 min interval config: 0 actual interval: 12062
D/PMS     (  915): releaseWL(43efbfe0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checking schedule, now: 1452523211111 next: 1452523229009
,I/CheckinService( 2178): active receiver: disabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014,
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(43edde08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): mActiveDefaultNetwork: WIFI
,D/GCM     ( 1378): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  915): releaseWL(43f87b18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/GAV4    ( 4599): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  915): releaseWL(42e35988): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  915): NetTransition Wakelock for ConnectedState released by timeout
,W/dalvikvm( 4553): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4553): threadid=1: thread exiting with uncaught exception (group=0x41957e30)
,E/ActivityManager(  915): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4553): FATAL EXCEPTION: main
E/AndroidRuntime( 4553): Process: com.test.thalitest, PID: 4553
E/AndroidRuntime( 4553): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4553): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4553): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4553): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4553): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4553): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4553): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4553): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4553): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4553): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4553): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4553): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4553): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4553): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4553): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  915):   Force finishing activity com.test.thalitest/.MainActivity
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Process (  915): killProcessQuiet, pid=4453
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  915): Killing 4453:com.android.settings:remote/1000 (adj 15): empty #17
,V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  915): [AlarmQueuing] connectivity wifi: true
I/ActivityManager(  915): Recipient 4453
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process ( 4553): killProcess, pid=4553
,D/Process ( 4553): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  915): bSetPropertyMultiRAB:false
,D/Tethering(  915): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  915): NoActiveNetworkState
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4743/10079)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
I/Tethering(  915): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
I/Tethering(  915): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  915): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  915): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  915): Found interface wlan0
,D/Tethering(  915): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1629/10029)
D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 4663): type=WIFI subType= reason=null isConnected=true
,I/ConnectivityHelper( 1278): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.musicenhancer (3870/10053)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.google.android.music (4663/10154)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.htc.launcher (1278/10076)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1629/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
D/PMS     (  915): acquireWL(42830b78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 915 1000 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  915): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  915): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  915): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  915): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  915): acquireWL(4297dc30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
D/PMS     (  915): releaseWL(4297dc30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  915): releaseWL(42830b78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,W/InputDispatcher(  915): channel '428a4450 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  915): channel '428a4450 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1937/10021)
I/ActivityManager(  915): Recipient 4553
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  915): Client connection lost with reason: 4
,W/InputDispatcher(  915): Attempted to unregister already unregistered input channel '428a4450 com.test.thalitest.MainActivity (s)'
,E/ExternalAccountType( 1347): Unsupported attribute readOnly
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
I/ActivityManager(  915): Process com.test.thalitest (pid 4553) has died.
,I/WindowState(  915): WIN DEATH: Window{428a4450 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/WindowManager(  915): WINDOW DIED Window{428a4450 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/InputMethodManagerService(  915): Got RemoteException sending setActive(false) notification to pid 4553 uid 10389
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/Binder  ( 1214): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1214): java.lang.NullPointerException
W/Binder  ( 1214): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1214): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1214): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1214): 	at dalvik.system.NativeStart.run(Native Method)
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4743): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4743): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4775/10151)
,D/AutoSetting( 1320): service - onStartCommand() screen is off, don't request location
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (3552/10160)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (3552/10160)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2178): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2178): num queued entries: 0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
I/iu.UploadsManager( 2178): num updated entries: 0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
I/iu.SyncManager( 2178): NEXT; no task
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/PMS     (  915): acquireWL(4284dd08): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1378): [NET] getaddrinfo-,err=8
D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1378): [NET] getaddrinfo-, 1
D/libc    ( 1378): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c669 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 230
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1378): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1378): [NET] getaddrinfo-,err=8
,D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1378): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/PMS     (  915): acquireWL(4350c488): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(4284dd08): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: starting a change hold
,D/PMS     (  915): releaseWL(4350c488): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(443b7dd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
,D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
,D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(443b7dd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,W/fb4a(:<default>):UserScope( 4683): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4683): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  915): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=30 [10][3][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4683): Called registerBroadcastReceiver twice.
,D/PMS     (  915): acquireWL(42d47020): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4663 10154 null
,W/ContextImpl( 4663): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4663, uid=10154, userID:0
,I/MusicLeanback( 4663): Conditions not met for autocaching.
,I/MusicLeanback( 4663): Stop autocaching.
,W/ContextImpl( 4663): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  915): releaseWL(42d47020): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4683/10027)
,D/PMS     (  915): releaseWL(43198638): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  915): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-,err=8
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  915): [NET] getaddrinfo-, 1
,D/libc    (  915): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8d68 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS,
D/libc    (  915): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  915): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4775): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  915): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  915): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1530): service - handleMessage() stop self,
,D/AutoSetting( 1530): service - onDestroy() END
,D/AutoSetting( 1530): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - requestNLP() NetworkLocationProvider not enabled
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  915): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  915): Waited long enough for: ServiceRecord{43f83e38 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  915): acquireWL(4293ab40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4293ab40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43a7ec08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  915): releaseWL(43a7ec08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,I/HtcPowerSaver(  915): >> updateStatus
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  915): acquireWL(42799950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{426103e0: PendingIntentRecord{427d8710 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123882, Int=0
,V/AlarmManager(  915): sending alarm PendingIntent{42004380: PendingIntentRecord{42c4c470 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135167, Int=0
,V/AlarmManager(  915): sending alarm PendingIntent{42607860: PendingIntentRecord{427babf0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452523229009, Int=522937000
,D/PMS     (  915): acquireWL(43a6f990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=9 [11][1][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  915): acquireWL(428a1c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(428a1c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43a6f990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/PMS     (  915): acquireWL(42e34558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(42e34558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43a1a538): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(44400928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  915): releaseWL(42799950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(42d428e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2178): Checkin interval check for package: unspecified last checkin: 1452523199040 min interval config: 0 actual interval: 41316
D/PMS     (  915): releaseWL(43a1a538): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,I/CheckinService( 2178): Checking schedule, now: 1452523240368 next: 1452523229009
,I/CheckinService( 2178): active receiver: enabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2178, uid=10029, userID:0
,I/CheckinService( 2178): Preparing to send checkin request
,I/EventLogService( 2178): Accumulating logs since 1452523196202
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
D/PMS     (  915): acquireWL(43921108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  915): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  915): acquireWL(44410d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1229): Vacuum at: now=1452523240498 tag=VacuumService
,D/PMS     (  915): releaseWL(44400928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43921108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43f19de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(43f19de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43ae5f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(44410d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/ConnectivityService(  915): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/PMS     (  915): releaseWL(43ae5f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  915): acquireWL(429d2dd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,V/GLSActivity( 1378): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  915): releaseWL(429d2dd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1378): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  915): acquireWL(42972920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(42972920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43792958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL,
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128,
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): acquireWL(42e31de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42e31de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(431f2cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43792958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4430f350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(4430f350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=343911938
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,I/WVCdm   (  372): CdmEngine::CloseSession
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,W/Settings( 4491): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1229): Scheduling Phenotype for one-off execution 13312 seconds from now (1452523241317)
,D/GetConfigurationSnapshotOperation( 1229): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (4491/10029)
,I/Adreno-EGL( 4491): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4491): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4491): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4491): Local Branch: 
I/Adreno-EGL( 4491): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4491): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4491):                  aa63bbd948f41d15fc72f585e
,I/PhenotypeFlagCommitter( 1229): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1229): Using platform SSLCertificateSocketFactory
,I/Adreno-EGL( 4491): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4491): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4491): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4491): Local Branch: 
I/Adreno-EGL( 4491): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4491): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4491):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4491): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4491): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4491): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4491): Local Branch: 
I/Adreno-EGL( 4491): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4491): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4491):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2867032269
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,I/WVCdm   (  372): CdmEngine::CloseSession
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1229): [NET] getaddrinfo-,err=8
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1229): [NET] getaddrinfo-, 1
D/libc    ( 1229): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6352 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 263,
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1229): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1229): [NET] getaddrinfo-,err=8
D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1229): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2178): [NET] getaddrinfo-,err=8
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2178): [NET] getaddrinfo-, 1
,D/libc    ( 2178): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a910 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 124,
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2178): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
,D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
D/libc    ( 2178): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2178): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2178): Sending checkin request (12398 bytes)
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1320): service - has update message, not stop
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1530): service - onCreate()
,D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate,
,D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  915): batLight: Full, plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c800
D/qdlights(  915): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1617): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1617): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1530): service - mHandler: update timezone
,D/AutoSetting( 1530): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1530): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1530): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1530): service - showManualTimeZoneSelector() send notification (single)
,I/PhoneStatusBar( 1122): removeNotification.gc:52
D/DotMatrix( 1617): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1617): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/PMS     (  915): releaseWL(431f2cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/RemoteViews( 1122): com.htc.htclocationservice (true,33751552)
D/PMS     (  915): acquireWL(443a4b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41edc728 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1122): com.htc.htclocationservice 3 11 4 11
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(443a4b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43e17760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=12 [8][1][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(43e17760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2178): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  915): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2178): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  915): getNetworkInfo networkType=9 called by com.google.android.gms (2178/10029)
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,I/CheckinRequestBuilder( 2178): Classify the device as Phone.
,I/CheckinTask( 2178): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2178): Checking schedule, now: 1452523243182 next: 1453046180174
,I/CheckinService( 2178): active receiver: disabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2178, uid=10029, userID:0
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,D/CheckinService( 2178): Recording last checkin time for package unspecified as 1452523243229
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(42d428e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2178/10029)
,D/GCM     ( 1378): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  915): acquireWL(4440fcd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{425c21f8: PendingIntentRecord{4274ae40 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141369, Int=0
,D/GpsLocationProvider(  915): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  915): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  915): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  915): acquireWL(44407760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 915 1000 null
D/PMS     (  915): releaseWL(4440fcd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  915): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-,err=8
D/libc    (  915): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  915): [NET] getaddrinfo-, 1
,D/libc    (  915): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7ea3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo_proxy-, success
I/global  (  915): call createSocket() return a new socket.
D/libc    (  915): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  915): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  915): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  915): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  915):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  915): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  915): acquireWL(442d5970): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4599 10111 null
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1278): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Launcher( 1278): Deferring update until onResume
,D/Launcher( 1278): waitUntilResume // bindAppsUpdated
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/ActivityManager(  915): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PMS     (  915): releaseWL(442d5970): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  915): Resuming delayed broadcast
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/ActivityManager(  915): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
,I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,E/ExternalAccountType( 1347): Unsupported attribute readOnly
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  915): acquireWL(425537d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3552 10160 null
,D/PMS     (  915): releaseWL(425537d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  915): acquireWL(431be490): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(431be490): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  915): acquireWL(41dad420): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(41dad420): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  915): acquireWL(43aa3570): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2178): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2178): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  915): Unable to load service info ResolveInfo{442cca68 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 851 ms] updated apps [took 851 ms] 
I/ActivityManager(  915): Resuming delayed broadcast
,D/RemoteDisplayProvider(  915): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  915): start
,D/PMS     (  915): releaseWL(44407760): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/GCoreNlp( 1229): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  915): applying state to connected service
D/PMS     (  915): acquireWL(4430ada0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(4430ada0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  915): applying state to connected service
,D/PMS     (  915): acquireWL(4293a6d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(4293a6d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4430eb20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(4430eb20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e1ce18 +
,I/Prism.WidgetManager( 1278): onLoadItems() +
,I/Icing   ( 2178): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,E/Prism.WidgetManager( 1278): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1278): onLoadItems() -
,I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e1ce18 -
,I/Icing   ( 2178): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  915): releaseWL(43aa3570): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1245): -- N1 =0
,D/PhoneApp( 1245): -- N2 =0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PhoneApp( 1245): -- N3 =0
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  915): Waited long enough for: ServiceRecord{43793358 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  915): acquireWL(42d3a0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=154934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(42d3a0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/Process (  915): killProcessQuiet, pid=3870
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3870:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/AutoSetting( 1530): service - handleMessage() stop self
,D/AutoSetting( 1530): service - onDestroy() END
,D/AutoSetting( 1530): service - handleMessage() quit looper
,D/Process (  915): killProcessQuiet, pid=3986
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3986:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  915): Recipient 3870
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 3986
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  915): acquireWL(4337d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end,
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(4337d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43ed51c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10027}
,V/AlarmManager(  915): sending alarm PendingIntent{437937b8: PendingIntentRecord{43c1bdb8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172101, Int=0
,D/PMS     (  915): releaseWL(43ed51c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  915): acquireWL(42981420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): releaseWL(42981420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(428c8cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=214934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(428c8cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43bafdf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43bafdf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(43ac53d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43ac53d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  915): acquireWL(43c1b420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=274935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43c1b420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  915): acquireWL(443e6e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(443e6e38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(43ae38b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43ae38b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43e31ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=334934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43e31ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(4319c248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4319c248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  915): acquireWL(431db7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=394935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(431db7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(43a91f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43a91f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(431dddd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=454934, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(431dddd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(43860e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43860e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  915): acquireWL(43a69b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=514935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43a69b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(439210c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(439210c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(428be780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=574934, Int=0
,D/PMS     (  915): releaseWL(428be780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(44395dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(44395dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  915): acquireWL(44372c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=634935, Int=0
,D/PMS     (  915): releaseWL(44372c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  915): killProcessQuiet, pid=4143
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4143:com.google.android.configupdater/u0a16 (adj 15): empty #17
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 4143
,D/PMS     (  915): acquireWL(44392000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(44392000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(431de6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=694934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(431de6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4283c840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4283c840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43f80258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=754935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43f80258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(429b6080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(429b6080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(44306f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=814935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(44306f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4350dab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(4350dab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
,D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(439aa048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(439aa048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(4413e818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=874934, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(4413e818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43addfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43addfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43f03c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=934935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43f03c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4436d838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4436d838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(42e3a938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=994935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(42e3a938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  915): Sampling interval elapsed, updating statistics ..
,D/PMS     (  915): acquireWL(439cb2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{420206b8: PendingIntentRecord{4271a8e8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784172, Int=0
,D/ConnectivityService(  915): Done.
,D/ConnectivityService(  915): Setting timer for 720seconds
,I/ActivityManager(  915): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4949 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  915): sending alarm PendingIntent{4269ac48: PendingIntentRecord{429b66a0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452523315724, Int=10800000
,V/AlarmManager(  915): sending alarm PendingIntent{428de348: PendingIntentRecord{42890da0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452523876207, Int=1800000
,V/AlarmManager(  915): sending alarm PendingIntent{4201b508: PendingIntentRecord{4299ddc8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452524036063, Int=900000
,V/AlarmManager(  915): sending alarm PendingIntent{42892128: PendingIntentRecord{443a2360 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452524110873, Int=0
,D/PMS     (  915): acquireWL(43a1f3d0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43ac9218): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43a1f3d0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4813): isEpsOn(), nState = 0
,D/PowerUsageService( 4813): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4813): MY_DEBUG = false
D/PMS     (  915): acquireWL(431e4a10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4813 1000 null
D/PMS     (  915): releaseWL(439cb2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/EventLogService( 2178): Aggregate from 1452523240412 (log), 1452522076060 (data)
,D/SmartSyncScreenOnOffTimeReceiver( 4813): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4813): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4813): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 4813): SettingOnTime = 1452578400000, randomSettingOnTime = 1452575396000
,D/SmartSyncScreenOnOffTimeReceiver( 4813): SettingOffTime = 1452564000000, randomSettingOffTime = 1452570581000
,D/SmartSyncScreenOnOffTimeReceiver( 4813): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4813): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4813): bNightModeTurnOffOnce = false
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.aurora (4949/10049)
W/BatSI   (  915): Couldn't get kernel wake lock stats
D/PMS     (  915): releaseWL(431e4a10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(43ac9218): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/Process (  915): killProcessQuiet, pid=4525
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4525:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4525
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(435223e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{431862b0: PendingIntentRecord{42a0cdd8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1007497, Int=0
,D/PMS     (  915): acquireWL(42703660): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42703660): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(435223e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(425e8ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1378/10029)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023725
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360023947
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024014
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025371
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360025387
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360028128
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029311
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360065830
,D/PMS     (  915): releaseWL(425e8ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=6 [142][9][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/PMS     (  915): acquireWL(423168f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(423168f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(431be3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1054935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(431be3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43a20490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43a20490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
,D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43ad9c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1114934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43ad9c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(424405a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(424405a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(420910a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(420910a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43abdaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1174934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43abdaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(427d6bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
D/PMS     (  915): releaseWL(427d6bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  915): BroadcastReceiver::onReceive+
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  915): acquireWL(42971f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1234935, Int=0
,D/PMS     (  915): releaseWL(42971f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4383eb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4383eb18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(443e7100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1294935, Int=0
,D/PMS     (  915): releaseWL(443e7100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(427ffc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/HtcPowerSaver(  915): updateBatteryInfo
,D/PMS     (  915): releaseWL(427ffc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1122): closing low battery warning: level=100
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,W/ContextImpl( 4813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,D/TetherSettings( 3792): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3792): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3792): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3792): Cust_ConnectToPC   : spcsc>false
D/        ( 3792): Cust_ConnectToPC   : IPT>true
,D/        ( 3792): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3792): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3792): Index of the first 1 = 3
W/ContextImpl( 3792): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3792): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3792): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3792): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3792): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3792): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3792): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43a7c720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1354934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43a7c720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(428af370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(428af370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  915): updateBatteryInfo
I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43adef00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(43adef00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(428b0348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1414934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(428b0348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43b67198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43b67198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(443c3f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(443c3f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(43aaeaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1474935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43aaeaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(428d4050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/BatteryService(  915): n_update end
D/PMS     (  915): releaseWL(428d4050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(42858cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(42858cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(443e8220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1534935, Int=0
,D/PMS     (  915): releaseWL(443e8220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(443b0a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(443b0a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43924050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(43924050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1122): closing low battery warning: level=100
,D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(443e74e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1594935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(443e74e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(44410e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
D/PMS     (  915): releaseWL(44410e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(4273c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,D/PMS     (  915): releaseWL(4273c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1122): closing low battery warning: level=100
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(434c6028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1654935, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(434c6028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(429cad58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(429cad58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(442d4960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1714934, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(442d4960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4317d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(4317d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(428fec60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  915): releaseWL(428fec60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43c326f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1774934, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43c326f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(428b4970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(428b4970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
,D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/PMS     (  915): acquireWL(443ee878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/PMS     (  915): releaseWL(443ee878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,I/HtcPowerSaver(  915): >> updateStatus
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  915): acquireWL(44391d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1834934, Int=0
,I/ProcessStatsService(  915): Prepared write state in 44ms
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(44391d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  915): Pruning old procstats: /data/system/procstats/state-2016-01-11-03-28-00.bin
,D/PMS     (  915): acquireWL(429a3328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(429a3328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
,D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1617): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1617): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  915): updateBatteryInfo
I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43ad8528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43ad8528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(429f1828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{424436a0: PendingIntentRecord{41fdd5b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1894935, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(429f1828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4993): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4993): ====startRecUseTime====
D/htc.customization.log.level( 4993):  is 
W/CustomizationLogLevel( 4993): Level value is invalid, use default level 2
D/CustomizationManager( 4993):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4993): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4993): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4993): Parsing tag category name = system
I/CustomizationCIDLoader( 4993): Parsing tag category name = application
I/CustomizationCIDLoader( 4993): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4993): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4993): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4993): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4993): Parsing tag category name = Settings
D/CustomizationManager( 4993):  Read CID file spent 0.160 (s)
D/CustomizationManager( 4993):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 4993): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4993): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4993): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4993): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  915): deletePackageAsUser: pkg=com.test.thalitest, pid=4993, uid=2000 user=0
D/Process (  915): killProcessQuiet, pid=4775
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  915): killProcessQuiet, pid=4760
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  915): killProcessQuiet, pid=4743
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
I/ActivityManager(  915): Killing 4775:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
I/ActivityManager(  915): Killing 4760:com.android.chrome/u0a96 (adj 15): empty for 1800s
I/ActivityManager(  915): Killing 4743:com.google.android.setupwizard/u0a79 (adj 15): empty for 1800s
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  915): killProcessQuiet, pid=4622
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  915): Killing 4622:com.htc.sense.mms/u0a65 (adj 15): empty for 1804s
I/ActivityManager(  915): Recipient 4760
I/ActivityManager(  915): Recipient 4743
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 4622
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  915): Copying FileAsset 0x62d79300 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  915): Recipient 4775
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  915): Skipping PackageSetting{4254b498 com.example.hello/10397} due to missing metadata
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1617): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1617): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1617): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1229): Ignoring removeGeofence because network location is disabled.
D/PMS     (  915): acquireWL(437a9108): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(437a9108): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1303): Cleaning up data for package: com.test.thalitest
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/Process (  915): killProcessQuiet, pid=4663
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "smsto"
I/Launcher( 1278): Deferring update until onResume
D/Launcher( 1278): waitUntilResume // bindAppsRemoved
I/ActivityManager(  915): Killing 4663:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  915): Recipient 4663
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  915): Client com.google.android.music (pid 4663): Died!
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  915): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1262): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/Prism.PackageStateRece_( 1278): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  915):   Scheme: "smsto"
E/ExternalAccountType( 1347): Unsupported attribute readOnly
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  915): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5008 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  915): acquireWL(425c21a8): PARTIAL_WAKE_LOCK  Icing 0x1 2178 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 356 ms] updated apps [took 356 ms] 
E/SQLiteDatabase( 5008): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5008): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5008): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5008): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5008): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5008): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5008): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5008): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5008): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5008): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5008): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5008): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5008): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5008): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5008): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5008): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5008): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5008): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5008): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5008): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5008): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5008): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5008): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5008): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5008): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5008): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5008): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5008): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5008): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5008): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5008): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5008): threadid=11: thread exiting with uncaught exception (group=0x41957e30)
E/AndroidRuntime( 5008): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5008): Process: com.google.android.apps.docs, PID: 5008
E/AndroidRuntime( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5008): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5008): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5008): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5008): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5008): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  915): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  915): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  915): 	... 5 more
E/SQLiteDatabase( 5008): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5008): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5008): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5008): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5008): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5008): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5008): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5008): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5008): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5008): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5008): Opened ClientFlag.db in read-only mode
D/Process ( 5008): killProcess, pid=5008
D/Process ( 5008): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  915): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5026 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  915): Recipient 5008
I/ActivityManager(  915): Process com.google.android.apps.docs (pid 5008) has died.
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 5026): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  915): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5040 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5026): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5026): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5026): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5026): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5026): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5026): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5026): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5026): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5026): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5026): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5026): threadid=10: thread exiting with uncaught exception (group=0x41957e30)
E/ActivityManager(  915): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5026): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5026): Process: com.android.keychain, PID: 5026
E/AndroidRuntime( 5026): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5026): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5026): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5026): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5026): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5026): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5026): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5026): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5026): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5026): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  915): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5026): killProcess, pid=5026
D/Process ( 5026): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  915): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  915): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452525014447.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  915): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  915): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  915): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  915): 	... 4 more
D/AppTag  ( 5040): getInstance(Context context)
D/AppTag  ( 5040): getInstance(Context context)
D/AppTag  ( 5040): onCreate()
W/PackageManager(  915): Unable to load service info ResolveInfo{43d93510 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  915): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  915): acquireWL(439921b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3552 10160 null
D/PMS     (  915): releaseWL(439921b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  915): Resuming delayed broadcast
W/dalvikvm( 4025): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  915): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2178): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2178): Clearing selected account for com.test.thalitest
I/ActivityManager(  915): Recipient 5026
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Process com.android.keychain (pid 5026) has died.
W/ActivityManager(  915): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  915): Resuming delayed broadcast
D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2178): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2178): Module APK com.google.android.play.games already loaded
I/ActivityManager(  915): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2178): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2178): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca33dc0
E/SQLiteDBG( 2178): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x663e8498
W/dalvikvm( 2178): threadid=45: thread exiting with uncaught exception (group=0x41957e30)
E/DriveAsyncService( 2178): disk I/O error (code 3850)
E/DriveAsyncService( 2178): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2178): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2178): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2178): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2178): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2178): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2178): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  915): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2178): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2178): Process: com.google.android.gms, PID: 2178
E/AndroidRuntime( 2178): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2178): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2178): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2178): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2178): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2178): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2178): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2178): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2178): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2178): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop148.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  915): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  915): 	... 5 more
D/Process ( 2178): killProcess, pid=2178
D/Process ( 2178): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  915): handleWLDeath(425c21a8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  915): Client connection lost with reason: 4
I/ActivityManager(  915): Recipient 2178
I/ActivityManager(  915): Process com.google.android.gms (pid 2178) has died.
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20997ms
I/ActivityManager(  915): Resuming delayed broadcast
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20991ms
E/SQLiteLog( 1378): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1378): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f8fa10
W/dalvikvm( 1378): threadid=1: thread exiting with uncaught exception (group=0x41957e30)
E/AndroidRuntime( 1378): FATAL EXCEPTION: main
E/AndroidRuntime( 1378): Process: com.google.process.gapps, PID: 1378
E/AndroidRuntime( 1378): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1378): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1378): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1378): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1378): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1378): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1378): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1378): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1378): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1378): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1378): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1378): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1378): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1378): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1378): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1378): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1378): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1378): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1378): 	... 10 more
E/ActivityManager(  915): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  915): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  915): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  915): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  915): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  915): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  915): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  915): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  915): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  915): 	... 5 more
D/Process ( 1378): killProcess, pid=1378
D/Process ( 1378): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  915): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5067 uid=10098 gids={50098, 3003, 5012}
D/RemoteDisplayProvider(  915): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  915): start
W/AtomicFile(  915): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  915): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DeviceManagement( 5067): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5067 dbg=false s=true
I/DeviceManagement( 5067): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5067): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5067): WorkflowService: Starting workflow service
I/DeviceManagement( 5067): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41db8ef0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5067): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5067): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5067): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5067): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 5067): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/ActivityManager(  915): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5081 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5067): SessionStateController: Checking invariants...
I/Prism.ItemManager( 1278): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1278): loadItems() com.htc.launcher.pageview.WidgetManager@41e1ce18 +
I/Prism.WidgetManager( 1278): onLoadItems() +
I/ActivityManager(  915): Recipient 1378
I/ActivityManager(  915): Process com.google.process.gapps (pid 1378) has died.
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  915): Client connection lost with reason: 4
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20809ms
D/Documents( 5081): Loading roots for com.android.providers.downloads.documents
D/Documents( 5081): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5081): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5081): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5081): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5081): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5081): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5081): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5081): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5081): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5081): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5081): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5081): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5081): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5081): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5081): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5081): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5081): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5081): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5081): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5081): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5081): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5081): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5081): threadid=1: thread exiting with uncaught exception (group=0x41957e30)
E/AndroidRuntime( 5081): FATAL EXCEPTION: main
E/AndroidRuntime( 5081): Process: com.android.documentsui, PID: 5081
E/AndroidRuntime( 5081): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5081): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5081): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5081): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5081): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5081): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5081): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5081): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5081): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5081): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5081): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5081): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5081): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5081): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5081): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5081): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5081): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5081): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5081): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5081): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5081): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5081): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5081): 	... 10 more

```
