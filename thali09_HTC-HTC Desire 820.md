#### Test 50650278923ff9f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
,--------- beginning of /dev/log/system
D/PMS     (  908): acquireWL(43fe9fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(43fe9fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 4560): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4560): ====startRecUseTime====
D/htc.customization.log.level( 4560):  is 
W/CustomizationLogLevel( 4560): Level value is invalid, use default level 2
D/CustomizationManager( 4560):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4560): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4560): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4560): Parsing tag category name = system
I/CustomizationCIDLoader( 4560): Parsing tag category name = application
I/CustomizationCIDLoader( 4560): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4560): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4560): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4560): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4560): Parsing tag category name = Settings
D/CustomizationManager( 4560):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4560):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 4560): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4560): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4560): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4560): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4560
D/PMS     (  908): acquireHCC(42652018): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(430f7c38): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x69c90c48 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1140937544
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
D/PMS     (  908): acquireWL(43be4480): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bdc768
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4572 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4572): Copying FileAsset 0x5c71b428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4572): Binding Chromium to main looper Looper (main, tid 1) {41a9b088}
I/LibraryLoader( 4572): Expected native library version number "",actual native library version number ""
I/chromium( 4572): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4572): Initializing chromium process, renderers=0
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425c5d10:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4572): 1101733456: getState(). Returning 12
D/PMS     (  908): acquireWL(43c83fb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  908): acquireWL(44080d98): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  908): releaseWL(43c83fb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4572): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4572): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4572): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4572): Local Branch: 
I/Adreno-EGL( 4572): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4572): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4572):                  aa63bbd948f41d15fc72f585e
W/chromium( 4572): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4572): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4572): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4572): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4572): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4572): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4572): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4572): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4572): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4572): CordovaWebView is running on device made by: HTC
,W/AwContents( 4572): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  908): Disable input method client, pid=1271
,W/ResourceType( 4572): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4572): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae6960, mServedView=org.apache.cordova.engine.SystemWebView{41aa9168 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  908): Enable input method client, pid=4572
,W/AwContents( 4572): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +380ms
,D/PMS     (  908): releaseWL(43be4480): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4572): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4572): JniHelper::setJavaVM(0x41572048), pthread_self() = 1662150472
,D/JX-Cordova( 4572): jxcore cordova android initializing
,I/SensorManager(  908): mEventCount = 1050
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 11.508MB for 64402-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 11.565MB for 96598-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 11.649MB for 144892-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 11.768MB for 217334-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 11.936MB for 325996-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 12.595MB for 733480-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 13.198MB for 1100216-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 14.109MB for 1650320-byte allocation
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 15.462MB for 2475476-byte allocation
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(42652018): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(430f7c38): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/dalvikvm-heap( 4572): Grow heap (frag case) to 17.556MB for 3713210-byte allocation
,W/jxcore-log( 4572): Initializing JXcore engine
,W/jxcore-log( 4572): JXcore engine is ready
,W/jxcore-log( 4572): Starting JXcore engine
,W/jxcore-log( 4572): Platform android
W/jxcore-log( 4572): 
,W/jxcore-log( 4572): Process ARCH arm
W/jxcore-log( 4572): 
,D/PMS     (  908): releaseWL(44080d98): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4572): JXcore Cordova bridge is ready!
I/jxcore-log( 4572): 
,W/jxcore-log( 4572): JXcore engine is started
,I/chromium( 4572): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  908): acquireWL(43bf6810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  908): sending alarm PendingIntent{422af758: PendingIntentRecord{4252c978 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105997, Int=0
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=305 rxSum=313} preTxRxSum={txSum=305 rxSum=313}
D/WifiDataStallTracker(  908): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19875 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19876 delay=15s
D/PMS     (  908): releaseWL(43bf6810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421f8c10
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421f8c10, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fb5240
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42245730
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  908): mWirelessDisplayManager is null
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 312ms
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
D/PMS     (  908): OOBE c monitor 11
D/NfcService( 1255): ScreenObserver: OFF
D/NfcService( 1255): applyRouting - 0
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43be66d8)
,D/NfcService( 1255): applyRouting -2
V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
D/PMN     (  908): wakingUp
I/InputMethodManagerService(  908): Disable input method client, pid=4572
D/PMS     (  908): acquireWL(4240d970): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
I/WindowManager(  908): No lock screen! windowToken=null
D/PMS     (  908): releaseWL(4240d970): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  908): onScreenOn
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): acquireWL(4304d070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(4304d070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/NfcService( 1255): applyRouting - 0
D/NfcService( 1255): applyRouting -2
D/MtpService( 1914): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1914): [MTP][onReceive]-
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PMS     (  908): acquireWL(41f6b8f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
,D/PMS     (  908): releaseWL(41f6b8f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1343): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
,V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19877 delay=15s
D/TetherSettings( 3927): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3927): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3927): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3927): Cust_ConnectToPC   : spcsc>false
D/        ( 3927): Cust_ConnectToPC   : IPT>true
D/        ( 3927): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3927): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3927): hasRemovableStorageSlot: true
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/SmartNS_Utility( 3927): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3927): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): SET_SCREEN_ON:On
I/wpa_supplicant( 1172): htc_wext_set_keepalive +
I/wpa_supplicant( 1172): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1172): getPrivFuncNum +	
I/wpa_supplicant( 1172): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING - ret = 0
I/ClockThread( 1116): stop update clock
,D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1343): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3927): onReceive:android.intent.action.USER_PRESENT
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,W/ContextImpl( 3927): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3927): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3927): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3927):  defaultType:0
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:362, mTXpacketCount:362, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  908): updateScreenOn: false
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4629 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  908): acquireWL(43c36e90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 4572): Toggling radios to true
I/jxcore-log( 4572): 
,D/BluetoothAdapter( 4572): enable(): BT is already enabled..!
D/PMS     (  908): releaseWL(43c36e90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(41ac11d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/WifiManager( 4572): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  908): New client listening to asynchronous messages
D/WifiService(  908): setWifiEnabled: true pid=4572, uid=10389
,D/PMS     (  908): releaseWL(41ac11d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1439
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  908): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1768): onScreenOn: false
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1768): onScreenOn: 1450280735778
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1768): onScreenOn: 1450280735778
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
,W/Settings:Agent(  908): << traceCallingStack(): 4(ms)
,D/WifiManager( 4572): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
D/WifiManager( 4572): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): TDLS: Tear down peers
,I/wpa_supplicant( 1172): wpa_driver_nl80211_disconnect(reason_code=3)
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4572): Radios toggled
I/jxcore-log( 4572): 
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fb5240
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fb5240, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42245730
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/jxcore-log( 4572): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4572): 
D/PMN     (  908): goingToSleep
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): acquireWL(423be9c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
I/jxcore-log( 4572): Perf Test app loaded loaded
I/jxcore-log( 4572): 
,I/jxcore-log( 4572): check test folder
I/jxcore-log( 4572): 
,I/jxcore-log( 4572): found test : ./testFindPeers.js
I/jxcore-log( 4572): 
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19877 mDataStallAlarmIntent=PendingIntent{42601830: PendingIntentRecord{4252c978 android broadcastIntent}}
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1172): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1172): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1172): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
D/wpa_supplicant( 1172): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1172): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1172): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1172): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1172): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7998bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1172):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1172): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1172): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1172): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1172): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1172): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1172): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1172): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1172): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1172): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1172): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1172): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1172): nl80211: if_removed already cleared -, ignore event
D/wpa_supplicant( 1172): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1172): nl80211: Event message available
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1172): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1172): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  908):    returned true
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): SET_SCREEN_ON:Off
I/wpa_supplicant( 1172): htc_wext_set_keepalive +
I/wpa_supplicant( 1172): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1172): getPrivFuncNum +	
I/wpa_supplicant( 1172): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1172): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1172): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1172): htc_wext_set_keepalive - ret = 0
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  908): release()
D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  908):    returned true
D/PMS     (  908): acquireWL(4243a108): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  908): acquireWL(41c3d600): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): Power_Mode_Type mode = 0
I/wpa_supplicant( 1172): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  908): [RunningState] Stop DHCP
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  908): doBoolean: RECONNECT
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): Fast associate: Old scan results
I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
,D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
D/PMS     (  908): acquireWL(44146790): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4629 1000 null
,D/NetworkPolicy(  908): updateScreenOn: false
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): Enter handleNetworkDisconnect
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/ContactMessageStore( 1242): start background delete task...
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19878 mDataStallAlarmIntent=null
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): Power_Mode_Type mode = 0
I/wpa_supplicant( 1172): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/ContactMessageStore( 1242): size: 0 , 0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 61
D/ContactMessageStore( 1242): Background delete complete
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/jxcore-log( 4572): found test : ./testSendData.js
I/jxcore-log( 4572): 
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/PMS     (  908): releaseWL(44146790): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
D/UsbnetStateTracker(  908): isAvailable+-
,D/WifiStateMachine(  908): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiNative-wlan0(  908): doBoolean: SET pno 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): CTRL_IFACE SET 'pno'='1'
,D/WISPrService( 3927): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  908): default: reconnect()
D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 3927): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 3927): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3927): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  908): New client listening to asynchronous messages
,D/SmartSyncUtils( 4629): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1172): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1172): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 3
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 1
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): selected network = 1
D/wpa_supplicant( 1172): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb799a4e8  current_ssid=0x0
D/wpa_supplicant( 1172): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1172): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1172): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1172): check if in concurrent case
,I/wpa_supplicant( 1172): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiNative-wlan0(  908):    returned true
D/wpa_supplicant( 1172): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1172): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1172): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1172): RSN: PMKSA cache search - network_ctx=0xb799a4e8 try_opportunistic=0
D/wpa_supplicant( 1172): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1172): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1172): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1172): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1172): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1172): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1172): nl80211: Unsubscribe mgmt frames handle 0xb7999718 (mode change)
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1172): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7999718
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Register frame type=0xd0 nl_handle=0xb7999718
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1172): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1172):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1172):   * freq=2412
D/wpa_supplicant( 1172):   * Auth Type 0
D/wpa_supplicant( 1172):   * WPA Versions 0x2
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1172): nl80211: Connect request send successfully
D/wpa_supplicant( 1172): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),famil,y 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/Process (  908): killProcessQuiet, pid=3989
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
V/NativeCrypto( 1376): Read error: ssl=0x663dd248: I/O error during system call, Connection timed out
V/NativeCrypto( 1376): SSL shutdown failed: ssl=0x663dd248: I/O error during system call, Broken pipe
D/libc    (  365): [NET] entry_id:4   entry:0xb7569350  removed 
D/libc    (  365): [NET] entry_id:13   entry:0xb7569ff0  removed 
D/libc    (  365): [NET] entry_id:11   entry:0xb7569e90  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb7569738  removed 
D/libc    (  365): [NET] entry_id:9   entry:0xb7569d08  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7569860  removed 
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActivityManager(  908): Killing 3989:com.google.android.music:main/u0a154 (adj 15): empty #17
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/PMS     (  908): releaseWL(4243a108): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
D/PMS     (  908): acquireWL(4320b180): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
D/libc    (  365): [NET] entry_id:10   entry:0xb7569dc8  removed 
D/libc    (  365): [NET] entry_id:12   entry:0xb7569f40  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7569428  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb7568fd8  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb7568d90  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb75690e8  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7569218  removed 
D/libc    (  365): [NET] entry_id:14   entry:0xb7568e48  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (519) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-49
I/wpa_supplicant( 1172): tsf=0000000021869975
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-50
I/wpa_supplicant( 1172): tsf=0000000107415372
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-77
I/wpa_supplicant( 1172): tsf=0000000021869990
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000021869993
I/wpa_supplicant( 1172): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
D/AutoSetting( 1343): service - mHandler: cancel location update
D/AutoSetting( 1343): service -           changes count: 0
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 21869975, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 107415372, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 21869990, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 21869993, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 4 to mScanResults
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  908): acquireWL(43930278): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3989
D/MediaRouterService(  908): Client com.google.android.music (pid 3989): Died!
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1376/10029)
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (4) end of scan result ==
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
D/WifiNative-wlan0(  908): doBoolean: SET pno 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1172): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: SCAN
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1172): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1172): Failed to initiate AP scan
I/wpa_supplicant( 1172): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  908):    returned true
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/PMS     (  908): releaseWL(4320b180): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  908): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  908): releaseWL(43930278): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WirelessDisplayService(  908): getDiscoveryDongleList
D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/SmartSyncUtils( 4629): getMobilePolicyEnabled, result = true
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] getTotalRam: 1873 Mb
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/WifiService(  908): New client listening to asynchronous messages
D/PMS     (  908): acquireWL(43a9e1d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43a9e1d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(440839f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1768): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1768): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1768): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1768): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1768): onScreenOff
D/PMS     (  908): releaseWL(440839f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/Choreographer( 4572): Skipped 104 frames!  The application may be doing too much work on its main thread.
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42245730
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42245730, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42245730, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42245730
,E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41e3fd90 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41e3fd90 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
I/chromium( 4572): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4572): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4572): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa9168 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/PMS     (  908): releaseWL(423be9c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/wpa_supplicant( 1172): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1172): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1172): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1172): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1172): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1172): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1172): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1172): nl80211: Connect event
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1172): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1172): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1172): Add randomness: count=8 entropy=1
I/wpa_supplicant( 1172): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1172): TDLS: Remove peers on association
D/wpa_supplicant( 1172): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1172): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1172): EAPOL: enable timer tick
D/wpa_supplicant( 1172): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1172): htc_wext_set_keepalive +
I/wpa_supplicant( 1172): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1172): getPrivFuncNum +	
I/wpa_supplicant( 1172): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1172): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1172): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1172): Get randomness: len=32 entropy=2
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
,D/Tethering(  908): interfaceStatusChanged wlan0, true
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
,D/WifiMonitor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiStateMachine(  908): Associated
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
D/WifiStateMachine(  908): BSSID was changed, update WiFi database
,I/wpa_supplicant( 1172): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb79999f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1172):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1172): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1172): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fbfb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1172):    broadcast key
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1172): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1172): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1172): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1172): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  908): updateConnectedAP...
E/wpa_supplicant( 1172): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1172): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1172): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1172): set send_ind_to_ndc = 0
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1172): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1172): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 1172): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1172): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1172): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1172): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1172): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1172): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1172): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1172): EAPOL authentication completed successfully
,I/wpa_supplicant( 1172): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiApDatabaseHandler(  908): updateConnectedAP...
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1172): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1172): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1172): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  908): This record is existed, only update it...
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3927): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WISPrService( 3927): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  908): doBoolean: SET pno 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  908):    returned true
D/DhcpStateMachine(  908): [StoppedState] Start DHCP
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(43c59c48): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): Power_Mode_Type mode = 1
I/wpa_supplicant( 1172): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1172): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  908):    returned null
D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4244a130 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4244a130 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4668 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
,D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  908): ipv4Default null
I/Tethering(  908): No IPv4 upstream interface, giving up.
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/PMS     (  908): acquireWL(43feb9b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1590/10029)
,D/PMS     (  908): releaseWL(43feb9b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  908): NoActiveNetworkState
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTING
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4423/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4423/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/wpa_supplicant( 1172): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1172): EAPOL: disable timer tick
,I/MusicStore( 4668): Database version: 95
,W/ContextImpl( 4668): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4668): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4668): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4668): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4668): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4668, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 4668): Registered
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
I/MediaRouter( 4668): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (4668/10154)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1914/10021)
,I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4688 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4668): getSelectedRoute
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4668/10154)
I/NetworkMonitor( 4668): type=WIFI subType= reason=null isConnected=false
,D/ACRA    ( 4688): ACRA is enabled for com.facebook.katana, intializing...
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4668, uid=10154, userID:0
,D/Process (  908): killProcessQuiet, pid=3969
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3969:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(43baf4d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43baf4d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ACRA    ( 4688): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4688): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4688): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4688): Preparing secondary program dexes.
V/DexLibLoader( 4688): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4688): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4688): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4688): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4688): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4688): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4688): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4688): Dex already copied
D/OdexVerifier( 4688): Odex verification is skipped.
,V/DexLibLoader( 4688): Creating class loader
,V/DexLibLoader( 4688): Finished creating class loader
V/DexLibLoader( 4688): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4688): Dex already copied
D/OdexVerifier( 4688): Odex verification is skipped.
,V/DexLibLoader( 4688): Creating class loader
,V/DexLibLoader( 4688): Finished creating class loader
V/DexLibLoader( 4688): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4688): Dex already copied
D/OdexVerifier( 4688): Odex verification is skipped.
,V/DexLibLoader( 4688): Creating class loader
,V/DexLibLoader( 4688): Finished creating class loader
V/DexLibLoader( 4688): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4688): Dex already copied
D/OdexVerifier( 4688): Odex verification is skipped.
,V/DexLibLoader( 4688): Creating class loader
,V/DexLibLoader( 4688): Finished creating class loader
,V/DexLibLoader( 4688): Verifying classes from secondary dexes.
,D/DexLibLoader( 4688): DexLibLoader.ensureDexLoaded took 21 ms
,I/ActivityManager(  908): Recipient 3969
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
W/dalvikvm( 4688): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  908):    returned true,
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0,
I/wpa_supplicant( 1172): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1172): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/dalvikvm( 4688): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4688): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4688): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4688): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4688): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,W/dalvikvm( 4688): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  908): releaseWL(43c59c48): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=33 [3][1][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): gateway: /192.168.1.1
,D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1172): htc_wext_set_keepalive +
I/wpa_supplicant( 1172): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1172): getPrivFuncNum +	
I/wpa_supplicant( 1172): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1172): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1172): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1172): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true,
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6,
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  908): WAN detection
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  908): default: setTeardownRequested(true)
,D/WISPrService( 3927): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): syncGetConfiguredNetworks
D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@42423120
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  908): acquireWL(42b90468): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  908): releaseWL(42b90468): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
,W/dalvikvm( 4688): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4688): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4688): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4688): Verify
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4688): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4688): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4688): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=4359
,I/ActivityManager(  908): Killing 4359:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  908): Recipient 4359
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,D/AutoSetting( 1343): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1343/10055)
,D/AutoSetting( 1343): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1343): service - onStartCommand() screen is off, don't request location
I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4739 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1343): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1343): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1343/10055)
,W/fb4a(:<default>):UserScope( 4688): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4688): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4688): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4739): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4739): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4739): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4739): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4753 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=4268
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 4268:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10079)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10079)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10079)
,D/PMS     (  908): acquireWL(426aefc8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Recipient 4268
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42641728): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2158): Checkin interval check for package: unspecified last checkin: 1450280687894 min interval config: 0 actual interval: 50929,
D/PMS     (  908): releaseWL(426aefc8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2158): Checking schedule, now: 1450280738831 next: 1450280717868
,I/CheckinService( 2158): active receiver: enabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2158, uid=10029, userID:0
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4768 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=4392
,I/ActivityManager(  908): Killing 4392:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/CheckinService( 2158): Preparing to send checkin request
,I/EventLogService( 2158): Accumulating logs since 1450280682966
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
,I/ActivityManager(  908): Recipient 4392
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4688): Grow heap (frag case) to 9.955MB for 84664-byte allocation
,I/CheckinRequestBuilder( 2158): Checkin reason type: 8 attempt count: 1
,E/dalvikvm( 4688): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4688): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2158): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4768): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4768): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4768): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm-heap( 4688): Grow heap (frag case) to 9.970MB for 28144-byte allocation
E/dalvikvm( 4688): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4688): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4688): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4688): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4688): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4688): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4688): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4688): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4688): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4688): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4688): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4688): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4688): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4688): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4688): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4688): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/PMS     (  908): releaseWL(41c3d600): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4768): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4768): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
V/Tethering(  908): bSetPropertyMultiRAB:false
,D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
,I/dalvikvm-heap( 4688): Grow heap (frag case) to 10.017MB for 39954-byte allocation
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/PMS     (  908): acquireWL(4401ce80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): releaseWL(4401ce80): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  908): NoActiveNetworkState
,I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [2][0][0]
,I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): Found interface wlan0
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4668): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1590/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1590/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10079)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (4016/10053)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4668/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4423/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(43898a68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4423/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
D/PMS     (  908): releaseWL(43898a68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(42375e98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/dalvikvm-heap( 4688): Grow heap (frag case) to 10.093MB for 79892-byte allocation
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
D/PMS     (  908): releaseWL(42375e98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1329): Unsupported attribute readOnly
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4768/10151)
,V/WebViewChromiumFactoryProvider( 4768): Binding Chromium to main looper Looper (main, tid 1) {41aa23b0}
,I/LibraryLoader( 4768): Expected native library version number "",actual native library version number ""
,I/chromium( 4768): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4768): Initializing chromium process, renderers=0
,D/PMS     (  908): acquireWL(42444e40): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  908): acquireWL(423a4848): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4768): BLUETOOTH permission is missing!
D/PMS     (  908): releaseWL(42444e40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4768): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4768): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4768): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4768): Local Branch: 
I/Adreno-EGL( 4768): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4768): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4768):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2158/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 4768): Starting up...
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4768/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4768/10151)
,I/dalvikvm-heap( 4688): Grow heap (frag case) to 10.277MB for 75760-byte allocation
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/Process (  908): killProcessQuiet, pid=4423
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3673/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3673/10160)
,I/ActivityManager(  908): Killing 4423:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425c4da0 u0 ReceiverList{42434580 4688 com.facebook.katana/10027/u0 remote:43b3dcf8}}
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425c4da0 u0 ReceiverList{42434580 4688 com.facebook.katana/10027/u0 remote:43b3dcf8}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43440340 u0 ReceiverList{434402e0 4688 com.facebook.katana/10027/u0 remote:42bbd788}}
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4808 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1914/10021)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,W/dalvikvm( 4808): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4808): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4808): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4808): install
,I/MultiDex( 4808): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4808): loading existing secondary dex files
,I/MultiDex( 4808): load found 3 secondary dex files
,I/MultiDex( 4808): install done
,D/PMS     (  908): acquireWL(441da900): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4808): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4808): VFY: unable to resolve instance field 36
,W/dalvikvm( 4808): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/AutoSetting( 1343): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4739): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4739): onReceive CONNECTIVITY_CHANGE networkType=1
,V/JNIHelp ( 4808): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PMS     (  908): releaseWL(441da900): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1343/10055)
I/ActivityManager(  908): Recipient 4423
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1343): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1343): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4768/10151)
,D/AutoSetting( 1343): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1343): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1343/10055)
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3673/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3673/10160)
,D/PMS     (  908): acquireWL(432cb240): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2158): Checkin interval check for package: unspecified last checkin: 1450280687894 min interval config: 0 actual interval: 51424
D/PMS     (  908): releaseWL(432cb240): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4688): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2158, uid=10029, userID:0
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4688): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4688): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 4808): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,W/dalvikvm( 4808): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/LocationInitializer( 2158): Restart initialization of location
,W/dalvikvm( 4808): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/AuthorizationBluetoothService( 1376): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1376): Proximity feature is not enabled.
,W/dalvikvm( 4808): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4808): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4808): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4808): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4808): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/MDM     ( 1222): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  908): acquireWL(43abab40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  908): releaseWL(43abab40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4808): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1529998906
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4808): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4808/10029)
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=423251628
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/Adreno-EGL( 4808): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4808): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4808): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4808): Local Branch: 
I/Adreno-EGL( 4808): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4808): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4808):                  aa63bbd948f41d15fc72f585e
W/ProcessCpuTracker(  908): Skipping unknown process pid 4838
,I/Adreno-EGL( 4808): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4808): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4808): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4808): Local Branch: 
I/Adreno-EGL( 4808): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4808): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4808):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4808): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4808): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4808): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4808): Local Branch: 
I/Adreno-EGL( 4808): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4808): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4808):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2158): Classify the device as Phone.
,D/libc    ( 2158): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2158): [NET] getaddrinfo-,err=8
D/libc    ( 2158): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2158): [NET] getaddrinfo-, 1
D/libc    ( 2158): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4dcf +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 297
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2158): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2158): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2158): [NET] getaddrinfo-,err=8
,D/libc    ( 2158): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2158): [NET] getaddrinfo-,err=8
D/libc    ( 2158): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2158): [NET] getaddrinfo-,err=8
,I/jxcore-log( 4572): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4572): 
,I/CheckinTask( 2158): Sending checkin request (12081 bytes)
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d47c +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,W/fb4a(:<default>):UserScope( 4688): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4688): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=17 [17][3][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4688): Called registerBroadcastReceiver twice.
,I/CheckinRequestBuilder( 2158): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2158): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/libc    ( 4688): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4688): [NET] getaddrinfo-,err=8
D/libc    ( 4688): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4688): [NET] getaddrinfo-, 1
,D/libc    ( 4688): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =9fa3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 52
D/libc    (  365): [NET]res_nsend:resplen=74
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4688): [NET] getaddrinfo_proxy-, success
I/global  ( 4688): call createSocket() return a new socket.
D/libc    ( 4688): [NET] getaddrinfo+,hn 11(0x33312e31332e39),sn(),family 0,flags 4
,D/libc    ( 4688): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2158/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=16 [6][1][0]
,D/PMS     (  908): releaseWL(423a4848): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinRequestBuilder( 2158): Classify the device as Phone.
,I/CheckinTask( 2158): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2158): Checking schedule, now: 1450280742138 next: 1450803679131
,I/CheckinService( 2158): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2158, uid=10029, userID:0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,I/CheckinService( 2158): Checking schedule, now: 1450280742186 next: 1450803679131
,I/CheckinService( 2158): active receiver: disabled
,D/CheckinService( 2158): Recording last checkin time for package unspecified as 1450280742191
D/PMS     (  908): acquireWL(42c4ff10): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4668 10154 null
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2158, uid=10029, userID:0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(42641728): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4668): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2158/10029)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4668, uid=10154, userID:0
D/PMS     (  908): releaseWL(42c4ff10): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4668): Conditions not met for autocaching.
I/MusicLeanback( 4668): Stop autocaching.
D/GCM     ( 1376): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1376): [NET] getaddrinfo-, 1
D/libc    ( 1376): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d8f6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  908): acquireWL(43b22958): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
W/ContextImpl( 4668): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 283
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1376): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4688): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4688): [NET] getaddrinfo-,err=8
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4688): Grow heap (frag case) to 10.992MB for 32784-byte allocation
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/PMS     (  908): acquireWL(4266c2e0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4688 10027 null
,D/PMS     (  908): acquireWL(436a03f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/PMS     (  908): releaseWL(43b22958): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
D/PMS     (  908): releaseWL(436a03f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(4304bcb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/PMS     (  908): releaseWL(4304bcb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4688/10027)
,D/AutoSetting( 1516): service - handleMessage() stop self
,D/AutoSetting( 1516): service - onDestroy() END
,D/AutoSetting( 1516): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4446
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4446:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4446
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=8 [23][2][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4768): Thread[GAThread,5,main]: No campaign data found.
,I/global  ( 4688): I/O error closing connection
I/global  ( 4688): java.net.SocketException: Socket is closed
I/global  ( 4688): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4688): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4688): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4688): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4688): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4688): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4688): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4688): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4688): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4688): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4688): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4688): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4688): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4688): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4688): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4688): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4688): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4688): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4688): Removing a connection that never existed!
,D/PMS     (  908): releaseWL(4266c2e0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/Process (  908): killProcessQuiet, pid=4410
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4410:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4410
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=4016
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4016:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4016
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4867 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  908):   Scheme: "mms"
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsUpdated
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
E/ExternalAccountType( 1329): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4867): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4867): MmsConfig.loadMmsSettings
,W/dalvikvm( 4867): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4867): VFY: unable to resolve instance field 36
,W/dalvikvm( 4867): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4867): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  908): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4890 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4867, uid=10111, userID:0
,W/Settings( 4867): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4867, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4867, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4867, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4867, uid=10111, userID:0
,D/MessageFrequencyProvider( 4890): onCreate
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4867, uid=10111, userID:0
,V/GetPrviateResource( 4890): GetPrviateResource
,D/PMS     (  908): acquireWL(43be6c28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4867 10111 null
D/MmsCustomizationProvider( 4890): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 4890): GetPrviateResource
,I/[PluginManager]RegisterService( 1343): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1343): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2878): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
D/MmsCustomizationProvider( 4890): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4867): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4867): MmsConfig.loadFromDatabase
I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  908): acquireWL(4265d3a8): PARTIAL_WAKE_LOCK  Icing 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426d4d70): PARTIAL_WAKE_LOCK  AsyncService 0x1 3673 10160 null
,D/PMS     (  908): releaseWL(4265d3a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426d4d70): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,E/Babel   ( 4867): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4867): MmsConfig.loadFromResources
,E/Babel   ( 4867): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4867): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  908): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
D/PMS     (  908): releaseWL(43be6c28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): acquireWL(43bda430): PARTIAL_WAKE_LOCK  Icing 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
,D/MessageCustFlag( 4890): sense_version=6.0
,I/ProviderInstaller( 4867): Installed default security provider GmsCore_OpenSSL
D/BTAccessoryUtil( 4890): createReceiver
,W/PackageManager(  908): Unable to load service info ResolveInfo{43b26368 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/BTAccessoryUtil( 4890): registerReceiver return intent = null
D/MessageCustFlag( 4890): sku_id=99
,W/SystemReader( 4890): Cannot find message_ambs_application_id, use default value instead
D/Process (  908): killProcessQuiet, pid=4464
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  908): Killing 4464:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Messaging( 4890): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4890): networkCode: 
D/MessageCustFlag( 4890): sku_id=99
D/MmsConfig( 4890): SIE smsPri: null
,D/MmsConfig( 4890): networkCode: 
I/ActivityManager(  908): Recipient 4464
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2158): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/HtcTelephonyCapability( 4890): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4890): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4890): getRATByHtcTelephonyCapability:1
W/SystemReader( 4890): Cannot find qct_8960_interface, use default value instead
I/PackageBroadcastService( 2158): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  908): Resuming delayed broadcast
,I/Icing   ( 2158): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  908): applying state to connected service
D/PMS     (  908): acquireWL(4416b3c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4416b3c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  908): applying state to connected service
,D/PMS     (  908): acquireWL(440ab050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(440ab050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(44092ed0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(44092ed0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2878): UpdateCorporaTask done [took 645 ms] updated apps [took 645 ms] 
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b2dc70 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/Icing   ( 2158): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2158): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(43bda430): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b2dc70 -
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,D/Messaging( 4890): mNeedToUpdateDate2 start
,D/MmsConfig( 4890): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4890): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4890): 
D/MmsAsyncWorkHandler( 4890): HM tk = 20001
D/ReportIndicatorCache( 4890): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4890): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aa34c0
,I/Messaging( 4890): mccmnc> 
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1242):  phoneType = -1
D/DraftCache( 4890): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4890): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4890): networkCode: 
,D/Messaging( 4890): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): sku_id=99
,D/MessageCustFlag( 4890): sense_version=6.0
,D/Jerry   ( 4890): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4890): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4890): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4890): createReceiver
,D/DraftCache( 4890): [DraftCache/484] rebuildCache
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1242): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1242): Update uri=content://mms, match=0
,V/MmsProvider( 1242): selection=st=129 AND m_type!=134
,D/Messaging( 4890): mNeedToUpdateDate2: false
,D/Messaging( 4890): Reset downloading state: 0
V/MmsSystemEventReceiver( 4890): TransactionService is going to be woken up.
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/TransactionService( 4890): 1-Creating TransactionService
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1242):  phoneType = -1
V/TransactionService( 4890): onStartCommand: 1
,D/MmsSystemEventReceiver( 4890): unRegisterForConnectionStateChanges
V/TransactionService( 4890): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4890): Loading previous transactions.
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1242): URI_DRAFT
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/Messaging( 4890): ViewCache CreatePreload
D/Messaging( 4890): ViewCache CreatePreloadOnlyMultipleOpsList
,D/AccFlag ( 1242): device_type: 1
,D/DraftCache( 4890): hasDraft() = false mNeedNotifyChange = true
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/DraftCache( 4890): [DraftCache/484] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4890): 
D/MmsAsyncWorkHandler( 4890): HM tk = 20002
,D/TransactionService( 4890): Force set service start id to 1
V/TransactionService( 4890): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4890): unRegisterForConnectionStateChanges
D/Cust_MMSMS( 4890): _has_set_default_values_2=true
V/TransactionService( 4890): Destroying TransactionService
,D/TransactionService( 4890): stopSelfResult: true, mLastHandledServiceId: 1
,D/Messaging( 4890): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,V/TransactionService( 4890): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1242): sku_id=99
,D/MsgPreferenceUtils( 4890): def_index: 0,
,D/MsgPreferenceUtils( 4890): globalIndex = 1
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1242): sku_id=99
,D/MsgPreferenceUtils( 4890): phone state: true
D/MsgPreferenceUtils( 4890): sd state: false
,D/MsgPreferenceUtils( 4890): vIndex = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(42bbd500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{43ac6d98: PendingIntentRecord{425d6660 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124399, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{433eb090: PendingIntentRecord{426040c0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450280750888, Int=1800000
,D/PMS     (  908): acquireWL(430ed5c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/PMS     (  908): acquireWL(44024420): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42bbd500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=6 [15][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): acquireWL(4401cde0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(44024420): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2158): Aggregate from 1450280738915 (log), 1450278950828 (data)
D/PMS     (  908): acquireWL(435a5580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(435a5580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(430ed5c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41e3f8c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(41e3f8c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42392d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
D/PMS     (  908): releaseWL(4401cde0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(424ccc48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(423d6b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1450280753097 tag=VacuumService
D/PMS     (  908): releaseWL(42392d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(424ccc48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(423d6b30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4255dcf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(4255dcf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4314a1a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(4314a1a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4359d428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(4359d428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42644f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(42644f80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): acquireWL(435c98b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42d9e8e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42d9e8e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43550738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(435c98b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4320ff60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(4320ff60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 7749 seconds from now (1450280753656)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
D/libc    ( 1222): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =42c8 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 250
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,I/GAV4    ( 4867): Thread[GAThread,5,main]: No campaign data found.
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/PMS     (  908): releaseWL(43550738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(44024578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(44024578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43c419d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [11][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(43c419d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(440e7a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(440e7a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/PMS     (  908): acquireWL(435a8e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=131526, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/PMS     (  908): releaseWL(435a8e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4304c720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{441430c8: PendingIntentRecord{4267f3b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137516, Int=0
,D/PMS     (  908): releaseWL(4304c720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/AutoSetting( 1343): service - mHandler: update timezone
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1516): service - onCreate()
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1578): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1578): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1516): service - mHandler: update timezone
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1516): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1516): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1578): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c59df8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 3 11
,D/AutoSetting( 1343): service - mHandler: update timezone
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1343): service - handleMessage() stop self
,D/AutoSetting( 1516): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1516): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1516): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1516): service - mHandler: update timezone
D/DotMatrix( 1578): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1578): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1343): service - handleMessage() quit looper
,D/AutoSetting( 1343): service - onDestroy() END
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1516): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1516): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1516): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1578): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e346a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  908): acquireWL(43c331f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4200f3e0: PendingIntentRecord{41b7e168 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141346, Int=0
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  908): acquireWL(4320b228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(43c331f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ef98 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  908): acquireWL(440101f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(440101f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(4320b228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  908): killProcessQuiet, pid=4495
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4495:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4495
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43c65a78 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1516): service - handleMessage() stop self
,D/AutoSetting( 1516): service - onDestroy() END
,D/AutoSetting( 1516): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4510
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4510:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4510
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43aba8f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10027}
,V/AlarmManager(  908): sending alarm PendingIntent{43890d60: PendingIntentRecord{43b6a428 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174876, Int=0
,D/PMS     (  908): releaseWL(43aba8f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(439069d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439069d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/PMS     (  908): acquireWL(43c41c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=191526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/PMS     (  908): releaseWL(43c41c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43c3d160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c3d160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4301bd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4301bd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43959e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=251526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43959e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4362d110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4362d110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43018fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=311527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43018fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426038d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(426038d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4572): Connected to the server!
I/jxcore-log( 4572): 
,I/chromium( 4572): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(430edf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(430edf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43585a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=371526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.609MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(43585a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(425de2c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425de2c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43466fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=431526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43466fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(440996c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(440996c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42c45178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=491526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42c45178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43b221b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b221b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(440511a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=551526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.610MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(440511a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4390dd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4390dd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44006ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=611526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44006ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/Process (  908): killProcessQuiet, pid=4234
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4234:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4234
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42686330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42686330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4312b2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=671527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4312b2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42c56ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42c56ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(436a12b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=731526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(436a12b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43468c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43468c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(429d43b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=791527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(429d43b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42c58e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42c58e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(434b86d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=851527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.610MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(434b86d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4380be28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4380be28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43aa9a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=911527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43aa9a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43932b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43932b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43b184d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=971526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.658MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(43b184d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(4339acf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d1a740: PendingIntentRecord{4242d8d8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784562, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4989 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  908): sending alarm PendingIntent{440a1570: PendingIntentRecord{43c72ba8 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5001 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{425b1f00: PendingIntentRecord{425b56b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450280840341, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{425985f8: PendingIntentRecord{425054d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450281560876, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{422472b8: PendingIntentRecord{42ba13f0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450281635958, Int=0
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4629): call getInstance()
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4629): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] bManual = false
D/PMS     (  908): acquireWL(439c97e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4629 1000 null
,D/PMS     (  908): releaseWL(4339acf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4629): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4629): SettingOnTime = 1450332000000, randomSettingOnTime = 1450330289000
D/SmartSyncScreenOnOffTimeReceiver( 4629): SettingOffTime = 1450317600000, randomSettingOffTime = 1450318325000
D/SmartSyncScreenOnOffTimeReceiver( 4629): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4629): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4629): bNightModeTurnOffOnce = false
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): releaseWL(439c97e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ImageRamCache( 4989): create image Cache, size: 31457280.
I/ImageRamCache( 4989): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4989): create image Cache, size: 12582912.
,I/FeedSettings( 4989): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4989): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4989): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4989): changeLocale(): en_GB
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (5001/10049)
,I/Prism.AllAppsOptionsMa_( 4989): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4989): loadGridSize() with Alternative
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/libc    ( 4989): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4989): [NET] getaddrinfo-,err=8
D/libc    ( 4989): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4989): [NET] getaddrinfo-, 1
,D/libc    ( 4989): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e770 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=206
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4989): [NET] getaddrinfo_proxy-, success
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/Process (  908): killProcessQuiet, pid=4542
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4542:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4542
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.launcher (4989/10076)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.launcher (4989/10076)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/Process (  908): killProcessQuiet, pid=4739
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4739:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4739
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43c37c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{420827e8: PendingIntentRecord{426cf790 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1014094, Int=0
,D/PMS     (  908): acquireWL(43c112b0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43c112b0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43c37c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43c10e40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023835
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024159
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024162
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024168
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024172
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025683
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025719
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028558
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360030029
,D/PMS     (  908): releaseWL(43c10e40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=2 [386][11][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(43bcaf88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43bcaf88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43bc3dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1031526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bc3dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43bbbdc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43bbbdc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43bb2360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1091526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bb2360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43bb1f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43bb1f48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43bb1c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1151526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bb1c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43b96178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b96178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43b95e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1211526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43b95e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(43b95b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b95b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43b8de18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1271526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43b8de18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43b81ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b81ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43b53360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1331526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43b53360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4392b980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4392b980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
,D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43634dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43634dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(435889c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1391527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(435889c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4345ee30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4345ee30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4331b070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1451527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4331b070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(432ad1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432ad1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43126040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1511526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43126040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43024bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43024bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42fc1828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1571526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fc1828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42d90650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42d90650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/PMS     (  908): acquireWL(425ce490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1631526, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/PMS     (  908): releaseWL(425ce490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4235a4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4235a4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(420ed788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(420ed788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/PMS     (  908): acquireWL(420de010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1691526, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): releaseWL(420de010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41a8fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(41a8fc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/PMS     (  908): acquireWL(4259e2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1751527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/PMS     (  908): releaseWL(4259e2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(41ca5a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41ca5a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43597e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1811527, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43597e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(42421e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42421e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/ProcessStatsService(  908): Prepared write state in 48ms
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-25.bin
,D/PMS     (  908): acquireWL(42f45978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(42f45978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3927): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3927): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3927): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3927): Cust_ConnectToPC   : spcsc>false
D/        ( 3927): Cust_ConnectToPC   : IPT>true
D/        ( 3927): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3927): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3927): Index of the first 1 = 3
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
W/Settings( 3927): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3927): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3927): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3927): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3927): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3927): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3927): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  908): acquireWL(423e6f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(423e6f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/PMS     (  908): acquireWL(42566400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ac59a8: PendingIntentRecord{41eac5c0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1871527, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): releaseWL(42566400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5039): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5039): ====startRecUseTime====
D/htc.customization.log.level( 5039):  is 
W/CustomizationLogLevel( 5039): Level value is invalid, use default level 2
D/CustomizationManager( 5039):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5039): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5039): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5039): Parsing tag category name = system
I/CustomizationCIDLoader( 5039): Parsing tag category name = application
I/CustomizationCIDLoader( 5039): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5039): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5039): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5039): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5039): Parsing tag category name = Settings
D/CustomizationManager( 5039):  Read CID file spent 0.161 (s)
D/CustomizationManager( 5039):  All configurations done spent 0.161 (s)
W/HtcNativeFlag( 5039): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5039): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5039): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5039): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=5039, uid=2000 user=0
D/Process (  908): killProcessQuiet, pid=4572
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
I/ActivityManager(  908): Killing 4572:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
D/Process (  908): killProcessQuiet, pid=4768
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4753
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Killing 4768:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  908): Killing 4753:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  908):   Force finishing activity ActivityRecord{425c2388 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  908): Copying FileAsset 0x620bdfb8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4768
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4753
E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 4572 uid 10389
E/JavaBinder( 1208): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  908): Skipping PackageSetting{421d3758 com.example.hello/10397} due to missing metadata
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  908): WIN DEATH: Window{42347990 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  908): Client connection lost with reason: 4
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1578): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1578): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1578): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): acquireWL(43be3fc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 4989): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4989): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  908): releaseWL(43be3fc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/VoicemailCleanupService( 1285): Cleaning up data for package: com.test.thalitest
W/SQLiteConnectionPool( 2158): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/Process (  908): killProcessQuiet, pid=4668
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  908): Killing 4668:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1343): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1343): handle notify Blinkfeed plugin client changed
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  908): Recipient 4668
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  908): Client com.google.android.music (pid 4668): Died!
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/IcingCorporaProvider( 2878): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
E/ExternalAccountType( 1329): Unsupported attribute readOnly
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5055 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  908): acquireWL(43b53360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  908): sending alarm PendingIntent{42611638: PendingIntentRecord{426cf790 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1914172, Int=0
D/PMS     (  908): acquireWL(43b50038): PARTIAL_WAKE_LOCK  Icing 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43b50038): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(4395bd20): PARTIAL_WAKE_LOCK  Icing 0x1 2158 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 2878): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2878): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x66599db8
E/IcingCorporaProvider( 2878): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2878): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2878): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2878): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2878): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2878): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2878): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2878): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2878): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2878): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2878): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2878): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2878): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2878): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2878): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2878): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2878): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2878): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2878): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2878): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2878): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2878): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2878): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2878): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2878): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2878): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2878): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2878): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2878): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2878): 	... 15 more
W/IcingCorporaProvider( 2878): notifyTableChanged failed.
W/IcingCorporaProvider( 2878): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2878): UpdateCorporaTask done [took 347 ms] updated apps [took 347 ms] 
D/PMS     (  908): releaseWL(4395bd20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/SQLiteDatabase( 5055): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5055): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5055): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5055): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5055): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5055): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5055): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5055): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5055): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5055): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5055): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5055): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5055): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5055): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5055): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5055): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5055): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5055): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5055): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5055): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5055): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5055): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5055): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5055): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5055): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5055): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5055): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5055): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5055): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5055): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5055): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5055): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5055): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5055): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5055): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5055): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5055): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5055): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5055): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5055): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5055): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5055): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5055): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5055): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5055): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5055): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5055): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5055): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5055): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5055): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5055): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5055): threadid=11: thread exiting with uncaught exception (group=0x4166ae30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5055): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5055): Process: com.google.android.apps.docs, PID: 5055
E/AndroidRuntime( 5055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5055): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5055): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5055): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5055): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5055): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
D/Process ( 5055): killProcess, pid=5055
D/Process ( 5055): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5074 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 5055
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 5055) has died.
W/ContextImpl( 5074): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5087 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5074): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5074): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5074): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5074): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5074): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5074): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5074): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5074): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5074): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5074): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5074): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5074): threadid=10: thread exiting with uncaught exception (group=0x4166ae30)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5074): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5074): Process: com.android.keychain, PID: 5074
E/AndroidRuntime( 5074): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5074): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5074): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5074): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5074): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5074): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5074): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5074): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5074): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5074): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5074): killProcess, pid=5074
D/Process ( 5074): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 5087): getInstance(Context context)
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450282543321.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
I/ActivityManager(  908): Recipient 5074
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 5074) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5087): getInstance(Context context)
D/AppTag  ( 5087): onCreate()
D/PMS     (  908): acquireWL(42415938): PARTIAL_WAKE_LOCK  AsyncService 0x1 3673 10160 null
D/PMS     (  908): releaseWL(42415938): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4193): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2158): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2158): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2158): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2158): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2158): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2158): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2158): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2158): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2158): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1376): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 2158): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca619e0
E/SQLiteDBG( 2158): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e3dd960
E/SQLiteDBG( 1376): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5c9b78a0
W/dalvikvm( 2158): threadid=42: thread exiting with uncaught exception (group=0x4166ae30)
W/dalvikvm( 1376): threadid=1: thread exiting with uncaught exception (group=0x4166ae30)
E/DriveAsyncService( 2158): disk I/O error (code 3850)
E/DriveAsyncService( 2158): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2158): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2158): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2158): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2158): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2158): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2158): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2158): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2158): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2158): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2158): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2158): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2158): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2158): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2158): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2158): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  908): Delay finish: com.google.android.gms/.gcm.GcmPackageTracker$GcmPackageChangeReceiver
E/AndroidRuntime( 1376): FATAL EXCEPTION: main
E/AndroidRuntime( 1376): Process: com.google.process.gapps, PID: 1376
E/AndroidRuntime( 1376): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1376): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1376): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1376): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1376): 	... 10 more
E/AndroidRuntime( 2158): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2158): Process: com.google.android.gms, PID: 2158
E/AndroidRuntime( 2158): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2158): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2158): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2158): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2158): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2158): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2158): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2158): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2158): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2158): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2158): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2158): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2158): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2158): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2158): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2158): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2158): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2158): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2158): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  908): App crashed! Process: com.google.process.gapps
D/Process ( 1376): killProcess, pid=1376
D/Process ( 1376): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
E/SQLiteDatabase( 2158): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2158): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2158): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2158): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2158): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2158): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2158): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2158): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2158): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2158): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2158): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2158): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2158): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2158): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2158): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2158): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2158): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2158): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2158): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2158): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2158): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2158): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2158): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2158): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2158): killProcess, pid=2158
D/Process ( 2158): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
W/PackageManager(  908): Unable to load service info ResolveInfo{4252fa70 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  908): Recipient 1376
I/ActivityManager(  908): Process com.google.process.gapps (pid 1376) has died.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
D/WifiService(  908): Client connection lost with reason: 4
I/Prism.ItemManager( 4989): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4989): loadItems() com.htc.launcher.pageview.WidgetManager@41b06730 +
I/Prism.WidgetManager( 4989): onLoadItems() +
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b2dc70 +
I/Prism.WidgetManager( 1271): onLoadItems() +
I/ActivityManager(  908): Recipient 2158
I/ActivityManager(  908): Process com.google.android.gms (pid 2158) has died.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10919ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20918ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20918ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20917ms
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Start proc com.google.process.gapps for broadcast com.google.android.gms/.gcm.nts.SchedulerReceiver: pid=5115 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20897ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20895ms
W/dalvikvm( 5115): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 5115): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5115): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5115): install
I/MultiDex( 5115): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5115): loading existing secondary dex files
I/MultiDex( 5115): load found 3 secondary dex files
I/MultiDex( 5115): install done

```
