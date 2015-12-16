#### Test 50650278e989a4f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
E/cutils-trace( 4418): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4418): ====startRecUseTime====
D/htc.customization.log.level( 4418):  is 
W/CustomizationLogLevel( 4418): Level value is invalid, use default level 2
D/CustomizationManager( 4418):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4418): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4418): Parsing tag category name = system
I/CustomizationCIDLoader( 4418): Parsing tag category name = application
I/CustomizationCIDLoader( 4418): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4418): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4418): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4418): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4418): Parsing tag category name = Settings
D/CustomizationManager( 4418):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4418):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4418): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4418): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4418): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4418): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4418
D/PMS     (  910): acquireHCC(440673d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(42485538): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x69f10f28 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1135527536
D/PMS     (  910): acquireWL(430349f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/FeedHostManager( 1276): [onPause]
I/FeedProviderManager( 1276): onPause
I/FeedHostManager( 1276): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d1d3d0
I/SocialFeedProvider( 1276): +onPause
I/SocialFeedProvider( 1276): -onPause
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4429 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1276): [trimMemory] 20
W/asset   ( 4429): Copying FileAsset 0x5c87f5e0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,V/WebViewChromiumFactoryProvider( 4429): Binding Chromium to main looper Looper (main, tid 1) {41adc670}
,I/LibraryLoader( 4429): Expected native library version number "",actual native library version number ""
,I/chromium( 4429): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4429): Initializing chromium process, renderers=0
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f24d88:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4429): 1101999632: getState(). Returning 12
D/PMS     (  910): acquireWL(44262528): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): acquireWL(442161c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): releaseWL(44262528): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4429): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4429): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4429): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4429): Local Branch: 
I/Adreno-EGL( 4429): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4429): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4429):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4429): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4429): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4429): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4429): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4429): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4429): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4429): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4429): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4429): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4429): CordovaWebView is running on device made by: HTC
,W/AwContents( 4429): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1276
,W/ResourceType( 4429): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4429): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b244c0, mServedView=org.apache.cordova.engine.SystemWebView{41aea128 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  910): Enable input method client, pid=4429
,W/AwContents( 4429): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +414ms
,D/PMS     (  910): releaseWL(430349f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4429): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4429): JniHelper::setJavaVM(0x415b7048), pthread_self() = 1663270200
,D/JX-Cordova( 4429): jxcore cordova android initializing
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 11.625MB for 144892-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 11.739MB for 217334-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 11.915MB for 325996-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 12.595MB for 733480-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 14.042MB for 1650320-byte allocation
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 15.457MB for 2475476-byte allocation
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(440673d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(42485538): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4429): Grow heap (frag case) to 17.472MB for 3713210-byte allocation
,W/jxcore-log( 4429): Initializing JXcore engine
,W/jxcore-log( 4429): JXcore engine is ready
,D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=101 rxSum=89} preTxRxSum={txSum=101 rxSum=89}
D/WifiDataStallTracker(  910): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  910): onDataStallAlarm: tag=19694 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19695 delay=15s
D/PMS     (  910): acquireWL(43c48c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{43c44948: PendingIntentRecord{424bbce0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104404, Int=0
,D/PMS     (  910): releaseWL(43c48c70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/jxcore-log( 4429): Starting JXcore engine
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,W/jxcore-log( 4429): Platform android
W/jxcore-log( 4429): 
,W/jxcore-log( 4429): Process ARCH arm
W/jxcore-log( 4429): 
,I/jxcore-log( 4429): JXcore Cordova bridge is ready!
I/jxcore-log( 4429): 
,W/jxcore-log( 4429): JXcore engine is started
,I/chromium( 4429): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  910): releaseWL(442161c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42134b88
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42134b88, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bb5c10
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@42425548
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 316ms
D/NfcService( 1257): ScreenObserver: OFF
,D/NfcService( 1257): applyRouting - 0
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426ceda8)
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
,D/NfcService( 1257): applyRouting -2
I/InputMethodManagerService(  910): Disable input method client, pid=4429
D/PMN     (  910): wakingUp
D/PMS     (  910): acquireWL(4269d708): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
I/WindowManager(  910): No lock screen! windowToken=null
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  910): releaseWL(4269d708): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  910): onScreenOn
,D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2431): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2431): [MTP][onReceive]-
D/PMS     (  910): acquireWL(42416388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(42416388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/NfcService( 1257): applyRouting - 0
D/NfcService( 1257): applyRouting -2
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/AutoSetting( 1347): receiver - intent: android.intent.action.USER_PRESENT
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): acquireWL(431f2b48): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  910): releaseWL(431f2b48): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/TetherSettings( 3781): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3781): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3781): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3781): Cust_ConnectToPC   : spcsc>false
D/        ( 3781): Cust_ConnectToPC   : IPT>true
D/        ( 3781): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3781): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3781): hasRemovableStorageSlot: true
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/SmartNS_Utility( 3781): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3781): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1347): service - onCreate()
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19696 delay=15s
,D/AutoSetting( 1347): service - AddressCache: using context: com.htc.Weather
,I/PSReceiver( 3781): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 3781): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3781): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3781):  defaultType:0
,D/LocationManagerService(  910): request 425bf1a0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/AutoSetting( 1347): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,W/ContextImpl( 3781): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ClockThread( 1119): stop update clock
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:On
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [ScoreAP] + current TXpacket:136, mTXpacketCount:136, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  910): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4482 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  910): updateScreenOn: false
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4482): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(425c42d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4482 1000 null
D/PMS     (  910): acquireWL(430ab050): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(430ab050): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4303aca8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(425c42d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  910): releaseWL(4303aca8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4482): getMobilePolicyEnabled, result = true
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOn: 1450233044510
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOn: 1450233044510
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bb5c10
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bb5c10, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@42425548
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(440970c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19696 mDataStallAlarmIntent=PendingIntent{42256340: PendingIntentRecord{424bbce0 android broadcastIntent}}
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:Off
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1186): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  910): acquireWL(4265b100): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,D/NetworkPolicy(  910): updateScreenOn: false
D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4482): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4482): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4482): isEpsOn(), nState = 0
,D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiService(  910): New client listening to asynchronous messages
D/PMS     (  910): releaseWL(4265b100): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42425548
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42425548, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42425548, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42425548
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4264d030 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4264d030 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  910): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  910): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  910): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  910): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  910): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  910): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  910): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(4300bc18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4300bc18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(435a98b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(435a98b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOff
,D/AutoSetting( 1347): service - mHandler: cancel location update
,D/AutoSetting( 1347): service -           changes count: 0
,I/jxcore-log( 4429): Toggling radios to true
I/jxcore-log( 4429): 
,D/BluetoothAdapter( 4429): enable(): BT is already enabled..!
,D/WifiManager( 4429): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1104
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
W/Settings:Agent(  910): << traceCallingStack(): 1(ms)
D/WifiManager( 4429): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
D/WifiManager( 4429): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): TDLS: Tear down peers
,I/wpa_supplicant( 1186): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiService(  910): setWifiEnabled: true pid=4429, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  910): New client listening to asynchronous messages
I/jxcore-log( 4429): Radios toggled
I/jxcore-log( 4429): 
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4429): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4429): 
I/jxcore-log( 4429): Perf Test app loaded loaded
I/jxcore-log( 4429): 
I/Choreographer( 4429): Skipped 81 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4429): check test folder
I/jxcore-log( 4429): 
,I/jxcore-log( 4429): found test : ./testFindPeers.js
I/jxcore-log( 4429): 
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1186): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1186): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1186): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1186): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb6fe4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1186):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1186): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1186): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_s,upplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1186): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1186): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
,D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(431d1e60): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,I/jxcore-log( 4429): found test : ./testSendData.js
I/jxcore-log( 4429): 
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ActivityManager(  910): Activity pause timeout for ActivityRecord{43cbf050 u0 com.test.thalitest/.MainActivity t2}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): Fast associate: Old scan results
I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19697 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910):    returned true
,D/WISPrService( 3781): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiService(  910): New client listening to asynchronous messages
,D/WISPrService( 3781): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1186): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,V/NativeCrypto( 1363): Read error: ssl=0x661e45f0: I/O error during system call, Connection timed out
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1186): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
V/NativeCrypto( 1363): SSL shutdown failed: ssl=0x661e45f0: I/O error during system call, Broken pipe
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 3
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 1
I/wpa_supplicant( 1186): wpa_s->is_screen_on 0
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): selected network = 1
D/WISPrService( 3781): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1186): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb6fe64e8  current_ssid=0x0
D/wpa_supplicant( 1186): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1186): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1186): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1186): check if in concurrent case
I/wpa_supplicant( 1186): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1186): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1186): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1186): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1186): RSN: PMKSA cache search - network_ctx=0xb6fe64e8 try_opportunistic=0
D/wpa_supplicant( 1186): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1186): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1186): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1186): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1186): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1186): nl80211: Unsubscribe mgmt frames handle 0xb6fe5718 (mode change)
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WISPrService( 3781): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1186): nl80211: Subscribe to mgmt frames with non-AP handle 0xb6fe5718
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb6fe5718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1186):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1186):   * freq=2412
D/wpa_supplicant( 1186):   * Auth Type 0
D/wpa_supplicant( 1186):   * WPA Versions 0x2
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1186): nl80211: Connect request send successfully
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1186): EAPOL,: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(430bc798): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/libc    (  363): [NET] entry_id:3   entry:0xb8167320  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8166fd8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8167428  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8167240  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb81670e8  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8162f60  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1186): reply (376) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-49
I/wpa_supplicant( 1186): tsf=0000000021860103
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-50
I/wpa_supplicant( 1186): tsf=0000000106742772
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=2
I/wpa_supplicant( 1186): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1186): freq=2427
I/wpa_supplicant( 1186): level=-78
I/wpa_supplicant( 1186): tsf=0000000021860118
I/wpa_supplicant( 1186): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1186): ssid=Gonzos
I/wpa_supplicant( 1186): ####
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 21860103, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 106742772, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 21860118, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1363/10029)
D/PMS     (  910): acquireWL(43b48e48): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1186): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): releaseWL(430bc798): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
D/WirelessDisplayService(  910): getDiscoveryDongleList
E/wpa_supplicant( 1186): send_and_recv error -16 - cmd 33
D/WifiNative-wlan0(  910):    returned true
D/wpa_supplicant( 1186): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1186): Failed to initiate AP scan
I/wpa_supplicant( 1186): Failed to initiate AP scan, Failed_to_scan_counter:1
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/PMS     (  910): releaseWL(43b48e48): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
W/ResourceType( 4429): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4429): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aea128 VFEDH.C. .F....ID 0,0-720,1134 #64}
I/chromium( 4429): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  910): releaseWL(440970c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1186): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1186): nl80211: Connect event
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1186): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1186): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1186): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1186): TDLS: Remove peers on association
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1186): EAPOL: enable timer tick
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1186): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1186): Get randomness: len=32 entropy=2
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1186): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fe59f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1186):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1186): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0eb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1186):    broadcast key
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1186): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1186): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1186): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1186): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,E/wpa_supplicant( 1186): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1186): set send_ind_to_ndc = 0
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 1186): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1186): EAPOL authentication completed successfully
I/wpa_supplicant( 1186): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  910): This record is existed, only update it...
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3781): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3781): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 1
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1186): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(43b2a820): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424bf368 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424bf368 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(43b2a820): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  910): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTING
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  910): NoActiveNetworkState
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4542 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43b5f8b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/PMS     (  910): releaseWL(43b5f8b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4272/10100)
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4272/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1186): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  910): WAN detection
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3781): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@424657f0
,D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 1186): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1186): EAPOL: disable timer tick
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(440deb38): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/MusicStore( 4542): Database version: 95
,W/ContextImpl( 4542): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,W/ContextImpl( 4542): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4542): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(440deb38): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4542): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4542): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4542, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4542): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
I/MediaRouter( 4542): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/NetworkMonitor( 4542): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4542/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2431/10021)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4575 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4542): getSelectedRoute
,I/NetworkMonitor( 4542): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4542/10154)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4542, uid=10154, userID:0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/Process (  910): killProcessQuiet, pid=3818
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42a89330): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(42a89330): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Killing 3818:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ACRA    ( 4575): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4575): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4575): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  910): Recipient 3818
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemClassLoaderAdder( 4575): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4575): Preparing secondary program dexes.
V/DexLibLoader( 4575): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4575): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4575): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4575): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4575): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4575): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4575): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4575): Dex already copied
D/OdexVerifier( 4575): Odex verification is skipped.
,V/DexLibLoader( 4575): Creating class loader
,V/DexLibLoader( 4575): Finished creating class loader
V/DexLibLoader( 4575): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4575): Dex already copied
D/OdexVerifier( 4575): Odex verification is skipped.
,V/DexLibLoader( 4575): Creating class loader
,V/DexLibLoader( 4575): Finished creating class loader
V/DexLibLoader( 4575): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4575): Dex already copied
D/OdexVerifier( 4575): Odex verification is skipped.
,V/DexLibLoader( 4575): Creating class loader
,V/DexLibLoader( 4575): Finished creating class loader
V/DexLibLoader( 4575): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4575): Dex already copied
D/OdexVerifier( 4575): Odex verification is skipped.
,V/DexLibLoader( 4575): Creating class loader
V/DexLibLoader( 4575): Finished creating class loader
,V/DexLibLoader( 4575): Verifying classes from secondary dexes.
,D/DexLibLoader( 4575): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4575): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4575): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4575): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4575): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4575): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4575): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4575): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PMS     (  910): releaseWL(431d1e60): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/CaptivePortalTracker(  910): NoActiveNetworkState
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(436c2320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4272/10100)
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4542/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,I/NetworkMonitor( 4542): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(426357c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1276/10076)
D/PMS     (  910): releaseWL(426357c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1276): [onReceive] WIFI(1): CONNECTED
D/PMS     (  910): releaseWL(436c2320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4272/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3879/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4575): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4575): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4575): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4575): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4575): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4575): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4575): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,I/ActivityManager(  910): Killing 4208:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4208
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  910): Recipient 4208
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,D/AutoSetting( 1347): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4598 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1347): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1347): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1347/10055)
,D/AutoSetting( 1347): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1347): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1347/10055)
,W/fb4a(:<default>):UserScope( 4575): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4575): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4575): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4598): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4598): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4598): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4598): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4612 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=4116
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 4116:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4598/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4598/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4598/10079)
,D/PMS     (  910): acquireWL(43c2a4b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43c1df40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1450232996684 min interval config: 0 actual interval: 51326
D/PMS     (  910): releaseWL(43c2a4b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checking schedule, now: 1450233048018 next: 1450233026652
,I/CheckinService( 2183): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2183, uid=10029, userID:0
,I/CheckinService( 2183): Preparing to send checkin request
,I/EventLogService( 2183): Accumulating logs since 1450232992240
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4627 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=4240
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/dalvikvm( 4575): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4575): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/ActivityManager(  910): Killing 4240:com.google.android.partnersetup/u0a32 (adj 15): empty #17
E/dalvikvm( 4575): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4575): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4575): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4575): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
E/dalvikvm( 4575): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4575): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4575): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  910): Recipient 4240
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4116
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/dalvikvm( 4575): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4575): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,I/dalvikvm-heap( 4575): Grow heap (frag case) to 9.959MB for 84664-byte allocation
,W/dalvikvm( 4575): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4575): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4575): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4575): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4575): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4575): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4575): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/GAV2    ( 4627): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4627): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4575): Grow heap (frag case) to 9.971MB for 28144-byte allocation
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4575): Grow heap (frag case) to 10.012MB for 39954-byte allocation
,I/dalvikvm-heap( 4575): Grow heap (frag case) to 10.087MB for 79892-byte allocation
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4646 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
,V/WebViewChromiumFactoryProvider( 4627): Binding Chromium to main looper Looper (main, tid 1) {41ae32e0}
,I/LibraryLoader( 4627): Expected native library version number "",actual native library version number ""
,I/chromium( 4627): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4627): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(4254a8b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  910): acquireWL(424c1d68): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4627): BLUETOOTH permission is missing!
D/PMS     (  910): releaseWL(4254a8b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4627): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4627): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4627): Local Branch: 
I/Adreno-EGL( 4627): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4627): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4627):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4646): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4646): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4646): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4646): install
,I/MultiDex( 4646): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4646): loading existing secondary dex files
,I/MultiDex( 4646): load found 3 secondary dex files
,I/MultiDex( 4646): install done
,I/NSApplication( 4627): Starting up...
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
W/dalvikvm( 4646): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4646): VFY: unable to resolve instance field 36
W/dalvikvm( 4646): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4646): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4044/10160)
,D/Process (  910): killProcessQuiet, pid=4272
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4575): Grow heap (frag case) to 10.275MB for 75760-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4044/10160)
I/ActivityManager(  910): Killing 4272:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Recipient 4272
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42647460 u0 ReceiverList{4258cd48 4575 com.facebook.katana/10027/u0 remote:440e4480}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42647460 u0 ReceiverList{4258cd48 4575 com.facebook.katana/10027/u0 remote:440e4480}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{431e4a58 u0 ReceiverList{431cc0f8 4575 com.facebook.katana/10027/u0 remote:42f052b8}}
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2431/10021)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 4646): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4646): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4646): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/PMS     (  910): acquireWL(42531e18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4646): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4646): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4646): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4646): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4646): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/PMS     (  910): releaseWL(42531e18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1347): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4598): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4598): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1347/10055)
,D/AutoSetting( 1347): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1347): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1347): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1347): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4627/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1347/10055)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4044/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4044/10160)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4575): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4575): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4575): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4044): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,D/NativeLibraryUtils( 4646): Install completed successfully. count=14 extracted=0
,D/LocationInitializer( 2183): Restart initialization of location
,E/MDM     ( 1225): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1363): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1363): Proximity feature is not enabled.
,D/WVCdm   (  370): PrepareKeyRequest: nonce=364373316
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  910): acquireWL(42b28a68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42b28a68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=4082158461
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/Adreno-EGL( 4646): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4646): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4646): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4646): Local Branch: 
I/Adreno-EGL( 4646): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4646): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4646):                  aa63bbd948f41d15fc72f585e
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bd6 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/Adreno-EGL( 4646): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4646): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4646): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4646): Local Branch: 
I/Adreno-EGL( 4646): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4646): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4646):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4646): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4646): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4646): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4646): Local Branch: 
I/Adreno-EGL( 4646): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4646): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4646):                  aa63bbd948f41d15fc72f585e
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4646/10029)
,W/Settings( 4646): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2183): [NET] getaddrinfo-, 1
,D/libc    ( 2183): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e85e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 250
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2183): Sending checkin request (12251 bytes)
,I/jxcore-log( 4429): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4429): 
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=26 [23][6][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,W/fb4a(:<default>):UserScope( 4575): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4575): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2183): Checking schedule, now: 1450233050772 next: 1450755987766
,I/CheckinService( 2183): active receiver: disabled
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,D/CheckinService( 2183): Recording last checkin time for package unspecified as 1450233050794
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(43c1df40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/PMS     (  910): acquireWL(43cbbf10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/GCM     ( 1363): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1363): [NET] getaddrinfo-,err=8
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1363): [NET] getaddrinfo-, 1
D/libc    ( 1363): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =537d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 221
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1363): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
E/fb4a(:<default>):LocalFbBroadcastManager( 4575): Called registerBroadcastReceiver twice.
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  910): acquireWL(4365f7b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/PMS     (  910): releaseWL(43cbbf10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/PMS     (  910): releaseWL(4365f7b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/PMS     (  910): acquireWL(431c73a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
D/ConnectivityService(  910): getActiveNetworkIn,fo called by com.facebook.katana (4575/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4575/10027)
D/PMS     (  910): releaseWL(431c73a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(424c1d68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(43cdd100): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4542 10154 null
,W/ContextImpl( 4542): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4542, uid=10154, userID:0
,I/MusicLeanback( 4542): Conditions not met for autocaching.
,I/MusicLeanback( 4542): Stop autocaching.
D/PMS     (  910): releaseWL(43cdd100): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4542): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=10 [10][1][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1514): service - handleMessage() stop self
,D/AutoSetting( 1514): service - onDestroy() END
,D/AutoSetting( 1514): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4295
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4295:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4295
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4627): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4259
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4259:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4259
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=3879
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3879:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3879
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4721 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1276): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1276): Deferring update until onResume
,D/Launcher( 1276): waitUntilResume // bindAppsUpdated
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4721): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4721): MmsConfig.loadMmsSettings
,W/dalvikvm( 4721): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4721): VFY: unable to resolve instance field 36
,W/dalvikvm( 4721): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4745 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,V/JNIHelp ( 4721): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4721, uid=10111, userID:0
,W/Settings( 4721): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4721, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4721, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4721, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4721, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4721, uid=10111, userID:0
,D/MessageFrequencyProvider( 4745): onCreate
,D/PMS     (  910): acquireWL(42f80238): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4721 10111 null
,D/MmsCustomizationProvider( 4745): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4745): GetPrviateResource
,V/GetPrviateResource( 4745): GetPrviateResource
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
D/MmsCustomizationProvider( 4745): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1347): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1347): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Resuming delayed broadcast
,I/Babel   ( 4721): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ProviderInstaller( 4721): Installed default security provider GmsCore_OpenSSL
,I/Babel   ( 4721): MmsConfig.loadFromDatabase
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42691470 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/IcingCorporaProvider( 2803): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  910): Resuming delayed broadcast
,E/Babel   ( 4721): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4721): MmsConfig.loadFromResources
,E/Babel   ( 4721): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4721): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/PackageManager(  910): Unable to load service info ResolveInfo{425d76f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  910): acquireWL(41c11bb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4044 10160 null
,D/PMS     (  910): acquireWL(42598a58): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4044): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
,D/MessageCustFlag( 4745): sense_version=6.0
,D/BTAccessoryUtil( 4745): createReceiver
,D/PMS     (  910): releaseWL(41c11bb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/BTAccessoryUtil( 4745): registerReceiver return intent = null
D/MessageCustFlag( 4745): sku_id=99
W/SystemReader( 4745): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4745): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4745): networkCode: 
,D/MessageCustFlag( 4745): sku_id=99
D/MmsConfig( 4745): SIE smsPri: null
,D/MmsConfig( 4745): networkCode: 
D/PMS     (  910): releaseWL(42f80238): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/HtcTelephonyCapability( 4745): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4745): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4745): getRATByHtcTelephonyCapability:1
,I/dalvikvm-heap( 4044): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
,W/SystemReader( 4745): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  910): Resuming delayed broadcast
,D/Process (  910): killProcessQuiet, pid=4317
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4317:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  910): Recipient 4317
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  910): Resuming delayed broadcast
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
,I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b72c10 +
,I/Prism.WidgetManager( 1276): onLoadItems() +
,I/IcingCorporaProvider( 2803): UpdateCorporaTask done [took 674 ms] updated apps [took 674 ms] 
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  910): acquireWL(43b21d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=121677, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b21d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/LocationProviderProxy(  910): applying state to connected service
,D/PMS     (  910): acquireWL(431f5ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): releaseWL(431f5ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42599600): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42599600): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4257fba8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4257fba8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42613c20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42613c20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1276): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1276): onLoadItems() -
,I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b72c10 -
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  910): releaseWL(42598a58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Messaging( 4745): mNeedToUpdateDate2 start
,D/MmsConfig( 4745): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4745): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4745): 
D/MmsAsyncWorkHandler( 4745): HM tk = 20001
,D/ReportIndicatorCache( 4745): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4745): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aef3c0
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,I/Messaging( 4745): mccmnc> 
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4745): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4745): [DraftCache/1] refresh
,D/MmsConfig( 4745): networkCode: 
,D/Messaging( 4745): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4745): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4745): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4745): createReceiver
,D/MessageCustFlag( 4745): sense_version=6.0
,D/Jerry   ( 4745): start to preload cursor >>>>>>>
,D/TelephUtils( 1242): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1242): Update uri=content://mms, match=0
V/MmsProvider( 1242): selection=st=129 AND m_type!=134
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/Messaging( 4745): Reset downloading state: 0
V/MmsSystemEventReceiver( 4745): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4745): 1-Creating TransactionService
V/TransactionService( 4745): onStartCommand: 1
,D/MmsSystemEventReceiver( 4745): unRegisterForConnectionStateChanges
V/TransactionService( 4745): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4745): Loading previous transactions.
,D/Messaging( 4745): mNeedToUpdateDate2: false
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1242): sku_id=99
,D/AccFlag ( 1242): device_type: 1
,D/TransactionService( 4745): Force set service start id to 1
V/TransactionService( 4745): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4745): unRegisterForConnectionStateChanges
,D/TransactionService( 4745): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4745): Destroying TransactionService
,D/DraftCache( 4745): [DraftCache/472] rebuildCache
,V/TransactionService( 4745): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4745): ViewCache CreatePreload
,D/Messaging( 4745): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4745): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1242): URI_DRAFT
,D/Cust_MMSMS( 4745): _has_set_default_values_2=true
D/PMS     (  910): acquireWL(43af3268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  910): sending alarm PendingIntent{436924c0: PendingIntentRecord{425c7c48 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123073, Int=0
D/PMS     (  910): releaseWL(43af3268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
D/DraftCache( 4745): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4745): [DraftCache/472] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4745): 
D/MmsAsyncWorkHandler( 4745): HM tk = 20002
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/MsgPreferenceUtils( 4745): def_index: 0
D/PMS     (  910): acquireWL(4312e440): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1242): sku_id=99
D/MsgPreferenceUtils( 4745): globalIndex = 1
D/MsgPreferenceUtils( 4745): phone state: true
D/MsgPreferenceUtils( 4745): sd state: false
D/MsgPreferenceUtils( 4745): vIndex = 0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1242): sku_id=99
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43193da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43193da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4312e440): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425e4350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(425e4350): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(437f37d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(426a3008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42edbf78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1225): Vacuum at: now=1450233061578 tag=VacuumService
D/PMS     (  910): releaseWL(437f37d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(426a3008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(426899d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42edbf78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(426899d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43491638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43491638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43c5b9c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(43c5b9c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43164bc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0,
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43164bc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(4395eb08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(4394b4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4394b4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4427caf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4395eb08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42665d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(42665d38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 7686 seconds from now (1450233062139)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1225): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
D/libc    ( 1225): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =da8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 296
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [12][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(4427caf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4328fac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(4328fac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(439931d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(439931d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4721): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(4353bca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(4353bca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43c33640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{42a8df00: PendingIntentRecord{42318ad8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136333, Int=0
,D/PMS     (  910): releaseWL(43c33640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,D/AutoSetting( 1347): service - mHandler: update timezone
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1514): service - onCreate()
,D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1559): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1514): service - mHandler: update timezone
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1514): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1514): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41c337f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 2 11
,D/AutoSetting( 1347): service - mHandler: update timezone
,D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1514): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1559): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1514): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1514): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1514): service - mHandler: update timezone
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1514): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1514): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1347): service - handleMessage() stop self
,D/AutoSetting( 1514): service - showManualTimeZoneSelector() send notification (single)
,I/PhoneStatusBar( 1119): removeNotification.gc:51
,D/AutoSetting( 1347): service - handleMessage() quit looper
,D/AutoSetting( 1347): service - onDestroy() END
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ad67f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 9 5 11
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/PMS     (  910): acquireWL(4312c7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  910): sending alarm PendingIntent{42336848: PendingIntentRecord{424b0400 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141147, Int=0
D/PMS     (  910): acquireWL(42649e58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(4312c7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =42f2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(42649e58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  910): killProcessQuiet, pid=4348
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4348:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4348
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{431a1240 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(430b7918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(430b7918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1514): service - handleMessage() stop self
,D/AutoSetting( 1514): service - onDestroy() END
,D/AutoSetting( 1514): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4363
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4363:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4363
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43165030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{43c632d0: PendingIntentRecord{439b29b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174167, Int=0
,D/PMS     (  910): releaseWL(43165030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(430d3848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=181677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(430d3848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430aa2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430aa2b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1363): disconnect managed GoogleApiClient
,D/PMS     (  910): acquireWL(426a24f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(426a24f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(42fbdff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=241677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42fbdff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(4363b4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): releaseWL(4363b4f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(42700b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42700b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43654760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=301677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43654760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(434c1a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(434c1a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4429): Connected to the server!
I/jxcore-log( 4429): 
,I/chromium( 4429): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Process (  910): killProcessQuiet, pid=4007
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4007:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4007
,D/PMS     (  910): acquireWL(43414d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43414d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43959308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=361677, Int=0
,I/dalvikvm-heap( 1276): Grow heap (frag case) to 12.586MB for 50416-byte allocation
,D/PMS     (  910): releaseWL(43959308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(440a26c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440a26c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(435905e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(435905e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4365f188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=421677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4365f188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(420519a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  910): releaseWL(420519a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4263ff18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4263ff18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43b64208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=481678, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b64208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43631210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43631210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43c54a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=541677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43c54a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43449fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(43449fc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(440d1800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440d1800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(438a6e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=601677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438a6e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(433db588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(433db588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1242): sku_id=99
D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/PMS     (  910): acquireWL(43c28168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/PMS     (  910): acquireWL(431f1d48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,V/AlarmManager(  910): sending alarm PendingIntent{41d198c0: PendingIntentRecord{424d6310 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=637680, Int=0
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4853 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{425d4a68: PendingIntentRecord{4258ce90 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450233150508, Int=10800000
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4268dbb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(43c28168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
,D/PMS     (  910): releaseWL(431f1d48): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(4268dbb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4853/10049)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/Process (  910): killProcessQuiet, pid=4400
,I/ActivityManager(  910): Killing 4400:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4400
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(4409a360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4409a360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1119): closing low battery warning: level=100
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43cb0270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=661677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1276): Grow heap (frag case) to 12.635MB for 50416-byte allocation
,D/PMS     (  910): releaseWL(43cb0270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c7ff90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c7ff90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43baa708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43baa708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(439458a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=721677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(439458a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43945648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43945648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4343b2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4343b2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42e59940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=781677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42e59940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4266d7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{41d4c410: PendingIntentRecord{4246ffa8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783248, Int=0
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): releaseWL(4266d7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): acquireWL(4319f188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(4319f188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42548fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42548fa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=98
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetPhoneState( 1628): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderNotification, total:1
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,D/TetherSettings( 3781): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3781): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3781): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3781): Cust_ConnectToPC   : spcsc>false
D/        ( 3781): Cust_ConnectToPC   : IPT>true
D/        ( 3781): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3781): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3781): Index of the first 1 = -1
W/Settings( 3781): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3781): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3781): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3781): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3781): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3781): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3781): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(435ac1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=841677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(435ac1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425fb998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): releaseWL(425fb998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4262e498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(4262e498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425970a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=901677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425970a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42393e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): releaseWL(42393e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424f6238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424f6238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4236dea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=961678, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4236dea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(435f5048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(435f5048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42630c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42396b40: PendingIntentRecord{423951c0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450233870856, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{41f9d1b8: PendingIntentRecord{4322bb88 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450233944586, Int=0
,W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4482): call getInstance()
,D/SmartSyncUtils( 4482): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4482): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4482): [updateNmRange] bManual = false
D/PMS     (  910): acquireWL(42690bc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4482 1000 null
,D/PMS     (  910): releaseWL(42630c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4482): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4482): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4482): SettingOnTime = 1450245600000, randomSettingOnTime = 1450245588000
D/SmartSyncScreenOnOffTimeReceiver( 4482): SettingOffTime = 1450317600000, randomSettingOffTime = 1450324659000
D/SmartSyncScreenOnOffTimeReceiver( 4482): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4482): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4482): bNightModeTurnOffOnce = false
D/PMS     (  910): acquireWL(42624230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{430db368: PendingIntentRecord{430aaec0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450233944629, Int=0
D/PMS     (  910): releaseWL(42690bc0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/SmartSyncUtils( 4482): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4482): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4482): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 4482): turnOffMobile bCheckMobileData = false
D/LocationManagerService(  910): getProviders()=[gps, network]
,D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  910): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4482): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/PMS     (  910): releaseWL(42624230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncUtils( 4482): isCharging status = 2
D/SmartSyncDataLinkTurnOffService( 4482): turnOffWifi ui setting = true
D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4482): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4482): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4482): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4482): turnOffWifi bWifiConnected = true
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4482/1000)
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(4409b010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{426cd818: PendingIntentRecord{426cc7f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1012770, Int=0
,D/PMS     (  910): acquireWL(43ca4af0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43ca4af0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4409b010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42643508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  910): releaseWL(42643508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=8 [233][19][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(4369c390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1021677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4369c390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4313b580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4313b580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(431e6b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(431e6b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=99
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43127250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1081677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43127250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430b0a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430b0a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43ad9598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1141677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43ad9598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(431e46b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(431e46b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42fbaff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(42fbaff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43103680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{43139f90: PendingIntentRecord{434c05e0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450234124685, Int=0
,W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): releaseWL(43103680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4482): turnOffWifi ui setting = true
,D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4482): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4482): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4482): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4482): turnOffWifi bWifiConnected = true
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4482/1000)
D/LocationManagerService(  910): getProviders()=[gps, network]
D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  910): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4482): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4482): isCharging status = 2
,D/PMS     (  910): acquireWL(43b227d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1201677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b227d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c0fc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  910): n_update end
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(43c0fc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(43c82008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c82008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderNotification, total:0
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HeadsetPhoneState( 1628): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,D/TetherSettings( 3781): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3781): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3781): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3781): Cust_ConnectToPC   : spcsc>false
D/        ( 3781): Cust_ConnectToPC   : IPT>true
D/        ( 3781): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3781): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3781): Index of the first 1 = -1
W/ContextImpl( 3781): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3781): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3781): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3781): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3781): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3781): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(435a64f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1261678, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(435a64f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(431c6a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(431c6a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(431cf4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1321677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(431cf4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430dba08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430dba08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4258f2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1381677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4258f2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43999368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43999368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42641178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1441677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42641178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4393fdd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(4393fdd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43aa62c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1501678, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43aa62c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42ffcb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42ffcb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43543a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1561677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43543a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c279d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43c279d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43593ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1621677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43593ab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4403cf28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4403cf28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(435ae850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1681677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(435ae850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(429bafb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429bafb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43ca2a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1741677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43ca2a48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42632c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42632c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(42acc418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1801677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42acc418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(430de5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(430de5e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(430bb240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{41d4c410: PendingIntentRecord{4246ffa8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1503269, Int=0
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,I/ProcessStatsService(  910): Prepared write state in 50ms
,I/ProcessStatsService(  910): Prepared write state in 24ms
,V/AlarmManager(  910): sending alarm PendingIntent{41f79198: PendingIntentRecord{425b3ba8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820662, Int=1800000
,D/PMS     (  910): acquireWL(42fac7b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,V/AlarmManager(  910): sending alarm PendingIntent{426bb778: PendingIntentRecord{426c58b8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1847913, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{436e0ea8: PendingIntentRecord{42667d10 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450234202394, Int=1800000
,V/AlarmManager(  910): sending alarm PendingIntent{42396b40: PendingIntentRecord{423951c0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450234770856, Int=900000
,D/PMS     (  910): releaseWL(42fac7b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-15-27.bin
,D/LocationManagerService(  910): getAllProviders()=[passive, gps, network]
,D/PMS     (  910): acquireWL(44213858): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4482): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): acquireWL(441d4550): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44213858): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/EventLogService( 2183): Aggregate from 1450233048046 (log), 1450232402329 (data)
W/BatSI   (  910): Couldn't get kernel wake lock stats
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): releaseWL(430bb240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): releaseWL(441d4550): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(435b43b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41c83350: PendingIntentRecord{41ed3c18 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1861677, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1276): Grow heap (frag case) to 12.683MB for 50416-byte allocation
D/PMS     (  910): releaseWL(435b43b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425f5a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425f5a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  910): acquireWL(426334e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
E/cutils-trace( 4899): Error opening trace file: No such file or directory (2)
V/AlarmManager(  910): sending alarm PendingIntent{426a9ca0: PendingIntentRecord{426cc7f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1912841, Int=0
D/PMS     (  910): acquireWL(426d6920): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/Process (  910): killProcessQuiet, pid=4627
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=4612
D/PMS     (  910): releaseWL(426d6920): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Killing 4627:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  910): Killing 4612:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  910): killProcessQuiet, pid=4598
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/PMS     (  910): releaseWL(426334e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Killing 4598:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  910): Recipient 4612
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  910): acquireWL(42700cd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1363/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023791
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024023
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024027
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024074
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025487
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025506
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028319
D/PMS     (  910): releaseWL(42700cd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Recipient 4598
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4627
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 4899): ====startRecUseTime====
D/htc.customization.log.level( 4899):  is 
W/CustomizationLogLevel( 4899): Level value is invalid, use default level 2
D/CustomizationManager( 4899):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4899): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4899): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4899): Parsing tag category name = system
I/CustomizationCIDLoader( 4899): Parsing tag category name = application
I/CustomizationCIDLoader( 4899): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4899): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4899): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4899): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4899): Parsing tag category name = Settings
D/CustomizationManager( 4899):  Read CID file spent 0.168 (s)
D/CustomizationManager( 4899):  All configurations done spent 0.168 (s)
W/HtcNativeFlag( 4899): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4899): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4899): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4899): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4899, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  910): killProcessQuiet, pid=4429
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  910): Killing 4429:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  910): killProcessQuiet, pid=4542
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  910): Killing 4542:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  910):   Force finishing activity ActivityRecord{43cbf050 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  910): Copying FileAsset 0x6a2cb1a0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  910): Recipient 4542
D/MediaRouterService(  910): Client com.google.android.music (pid 4542): Died!
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  910): channel '41cc1218 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  910): channel '41cc1218 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowManager(  910): WINDOW DIED Window{41cc1218 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputDispatcher(  910): Attempted to unregister already unregistered input channel '41cc1218 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4429 uid 10389
W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
W/PackageSettings(  910): Skipping PackageSetting{4215dc60 com.example.hello/10397} due to missing metadata
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=4 [163][8][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(431954a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1289): Cleaning up data for package: com.test.thalitest
D/PMS     (  910): releaseWL(431954a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/[PluginManager]RegisterService( 1347): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1347): handle notify Blinkfeed plugin client changed
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Launcher( 1276): Deferring update until onResume
D/Launcher( 1276): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1276): action: android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/IcingCorporaProvider( 2803): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4914 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PMS     (  910): acquireWL(440ddf98): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2803): UpdateCorporaTask done [took 471 ms] updated apps [took 471 ms] 
E/SQLiteDatabase( 4914): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4914): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4914): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4914): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4914): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4914): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4914): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4914): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4914): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4914): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4914): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4914): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4914): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4914): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4914): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4914): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4914): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4914): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4914): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4914): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4914): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4914): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4914): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4914): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4914): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4914): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4914): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4914): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4914): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4914): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4914): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4914): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4914): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4914): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4914): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4914): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4914): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4914): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4914): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4914): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4914): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4914): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4914): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4914): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4914): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4914): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4914): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4914): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4914): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4914): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4914): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4914): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4914): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4914): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4914): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4914): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4914): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4914): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4914): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4914): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4914): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4914): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4914): threadid=11: thread exiting with uncaught exception (group=0x416afe30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4914): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4914): Process: com.google.android.apps.docs, PID: 4914
E/AndroidRuntime( 4914): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4914): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4914): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4914): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4914): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4914): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4914): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4914): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4914): 	at aho.run(AbstractDatabaseInstance.java:455)
D/Process ( 4914): killProcess, pid=4914
D/Process ( 4914): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4932 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
I/ActivityManager(  910): Recipient 4914
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4914) has died.
W/ContextImpl( 4932): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4945 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4932): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4932): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4932): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4932): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4932): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4932): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4932): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4932): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4932): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4932): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4932): threadid=10: thread exiting with uncaught exception (group=0x416afe30)
E/AndroidRuntime( 4932): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4932): Process: com.android.keychain, PID: 4932
E/AndroidRuntime( 4932): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4932): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4932): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4932): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4932): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4932): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4932): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4932): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4932): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4945): getInstance(Context context)
D/Process ( 4932): killProcess, pid=4932
D/Process ( 4932): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450234853052.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
D/AppTag  ( 4945): getInstance(Context context)
D/AppTag  ( 4945): onCreate()
I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  910): acquireWL(41e038f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4044 10160 null
D/PMS     (  910): releaseWL(41e038f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4932
I/ActivityManager(  910): Process com.android.keychain (pid 4932) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2183): Clearing selected account for com.test.thalitest
W/dalvikvm( 4070): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d12fc38
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x617d9450
W/dalvikvm( 2183): threadid=46: thread exiting with uncaught exception (group=0x416afe30)
I/LocationSettingsChecker( 2183): Removing dialog suppression flag for package com.test.thalitest
E/DriveAsyncService( 2183): disk I/O error (code 3850)
E/DriveAsyncService( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2183): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2183): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2183): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2183): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2183): Process: com.google.android.gms, PID: 2183
E/AndroidRuntime( 2183): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2183): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2183): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2183): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2183): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2183): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2183): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2183): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2183): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2183): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms
D/Process ( 2183): killProcess, pid=2183
D/Process ( 2183): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
W/PackageManager(  910): Unable to load service info ResolveInfo{4394ce18 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  910): Recipient 2183
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.gms (pid 2183) has died.
D/WifiService(  910): Client connection lost with reason: 4
D/PMS     (  910): handleWLDeath(440ddf98): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
I/ActivityManager(  910): Resuming delayed broadcast
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20993ms
E/SQLiteLog( 1363): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1363): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63739c10
W/dalvikvm( 1363): threadid=1: thread exiting with uncaught exception (group=0x416afe30)
I/Prism.ItemManager( 1276): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1276): loadItems() com.htc.launcher.pageview.WidgetManager@41b72c10 +
I/Prism.WidgetManager( 1276): onLoadItems() +
E/AndroidRuntime( 1363): FATAL EXCEPTION: main
E/AndroidRuntime( 1363): Process: com.google.process.gapps, PID: 1363
E/AndroidRuntime( 1363): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1363): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1363): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1363): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1363): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1363): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1363): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1363): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1363): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1363): 	... 10 more
E/ActivityManager(  910): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4972 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1363): killProcess, pid=1363
D/Process ( 1363): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 4972): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4972 dbg=false s=true
I/DeviceManagement( 4972): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4972): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4972): WorkflowService: Starting workflow service
I/DeviceManagement( 4972): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b0ef30] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4972): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4972): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4972): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4972): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 4972): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4986 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4972): SessionStateController: Checking invariants...
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 1363
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.google.process.gapps (pid 1363) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20819ms
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }

```
