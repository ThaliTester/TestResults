#### Test 56449660311ec66_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=136 rxSum=113} preTxRxSum={txSum=136 rxSum=113}
D/WifiDataStallTracker(  907): updateDataStallInfo: NONE
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19951 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19952 delay=15s
--------- beginning of /dev/log/system
D/PMS     (  907): acquireWL(4423fe40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42f1c210: PendingIntentRecord{424e5bc8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=101143, Int=0
D/PMS     (  907): releaseWL(4423fe40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 110
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
E/cutils-trace( 4438): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4438): ====startRecUseTime====
D/htc.customization.log.level( 4438):  is 
W/CustomizationLogLevel( 4438): Level value is invalid, use default level 2
D/CustomizationManager( 4438):  Read ACC file spent 0.059 (s)
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4438): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4438): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4438): Parsing tag category name = system
I/CustomizationCIDLoader( 4438): Parsing tag category name = application
I/CustomizationCIDLoader( 4438): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4438): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4438): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4438): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4438): Parsing tag category name = Settings
D/CustomizationManager( 4438):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4438):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4438): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4438): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4438): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4438): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4438
D/PMS     (  907): acquireHCC(42dd4130): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(430a9320): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x6283dce0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1113388712
D/PMS     (  907): acquireWL(42dca9b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c71820
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4449 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4449): Copying FileAsset 0x5c799648 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4449): Binding Chromium to main looper Looper (main, tid 1) {41b2c120}
I/LibraryLoader( 4449): Expected native library version number "",actual native library version number ""
I/chromium( 4449): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4449): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(42edf200): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(435c3e88): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4389e710:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4449): 1102326864: getState(). Returning 12
D/PMS     (  907): releaseWL(42edf200): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4449): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4449): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4449): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4449): Local Branch: 
I/Adreno-EGL( 4449): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4449): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4449):                  aa63bbd948f41d15fc72f585e
W/chromium( 4449): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4449): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4449): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4449): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4449): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4449): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4449): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4449): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4449): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4449): CordovaWebView is running on device made by: HTC
,W/AwContents( 4449): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +282ms
W/ResourceType( 4449): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4449): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b74340, mServedView=org.apache.cordova.engine.SystemWebView{41b39f68 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Disable input method client, pid=1273
I/InputMethodManagerService(  907): Enable input method client, pid=4449
,W/AwContents( 4449): nativeOnDraw failed; clearing to background color.
,D/PMS     (  907): releaseWL(42dca9b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4449): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4449): JniHelper::setJavaVM(0x416ed010), pthread_self() = 1664029976
,I/chromium( 4449): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 11.993MB for 42652-byte allocation
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 12.078MB for 95956-byte allocation
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 12.159MB for 143930-byte allocation
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 12.276MB for 215890-byte allocation
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 12.439MB for 323830-byte allocation
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 12.712MB for 485740-byte allocation
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 13.684MB for 1092904-byte allocation
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422386d0
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 14.632MB for 1639352-byte allocation
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422386d0, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c59280
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@427890d8
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 15.926MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42dd4130): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(430a9320): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 329ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4449
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@430ad808)
D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
D/NfcService( 1252): applyRouting -2
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMN     (  907): wakingUp
D/PMS     (  907): acquireWL(437cdc70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): releaseWL(437cdc70): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  907): onScreenOn
D/PMS     (  907): acquireWL(43f452c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43f452c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/ResourceType( 4449): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4449): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b39f68 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/AutoSetting( 1313): receiver - intent: android.intent.action.USER_PRESENT
,D/MtpService( 2383): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2383): [MTP][onReceive]-
,D/NfcService( 1252): applyRouting - 0
D/NfcService( 1252): applyRouting -2
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): acquireWL(43615678): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/PMS     (  907): releaseWL(43615678): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/TetherSettings( 3837): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3837): Cust_ConnectToPC   : Internet_Sharing>true
D/AutoSetting( 1313): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/        ( 3837): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3837): Cust_ConnectToPC   : spcsc>false
D/        ( 3837): Cust_ConnectToPC   : IPT>true
D/        ( 3837): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,E/SmartNS_Utility( 3837): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3837): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3837): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19953 delay=15s
,I/PSReceiver( 3837): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:On
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): BG scan when screen On
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): Match BG scan, scan!
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
I/SmartNS_PSService( 3837): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3837):  defaultType:0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1114): stop update clock
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  907): updateScreenOn: false
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4504 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  907): acquireWL(43d51948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(43d51948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43f224e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4449): Grow heap (frag case) to 18.066MB for 3688532-byte allocation
,D/PMS     (  907): releaseWL(43f224e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): onScreenOn: 1453367874092
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1772): onScreenOn: 1453367874092
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c59280
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c59280, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@427890d8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl( 4504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(4328b778): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/AlarmManager(  907): ACTION_SCREEN_OFF
,I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19953 mDataStallAlarmIntent=PendingIntent{4269bd28: PendingIntentRecord{424e5bc8 android broadcastIntent}}
,D/SmartSyncUtils( 4504): isEpsOn(), nState = 0
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/PMS     (  907): acquireWL(44349b48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4504 1000 null
D/PMS     (  907): releaseWL(4328b778): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
D/PMS     (  907): acquireWL(43b2f5d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/PMS     (  907): releaseWL(44349b48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4504): getMobilePolicyEnabled, result = true
,D/Process (  907): killProcessQuiet, pid=3872
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3872:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3872
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/jxcore-log( 4449): Initializing JXcore engine
,W/jxcore-log( 4449): JXcore engine is ready
,W/jxcore-log( 4449): Starting JXcore engine
,W/jxcore-log( 4449): Platform android
W/jxcore-log( 4449): 
,W/jxcore-log( 4449): Process ARCH arm
W/jxcore-log( 4449): 
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 182
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:Off
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
I/SensorManager(  907): mEventCount = 1200
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,W/ContextImpl( 4504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4504): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4504): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4504): isEpsOn(), nState = 0
,D/WifiService(  907): New client listening to asynchronous messages
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427890d8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427890d8, eanble = 0, strlen(mName) = 36
,W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427890d8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427890d8
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42789650 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42789650 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/AutoSetting( 1313): service - mHandler: cancel location update
D/AutoSetting( 1313): service -           changes count: 0
D/PMS     (  907): acquireWL(43f21550): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): releaseWL(43f21550): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44333ad8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44333ad8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1772): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1772): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1772): onScreenOff
,D/PMS     (  907): releaseWL(435c3e88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4449): JXcore Cordova bridge is ready!
I/jxcore-log( 4449): 
,W/jxcore-log( 4449): JXcore engine is started
,E/jxcore  ( 4449): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4449): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4449): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  907): killProcessQuiet, pid=4227
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  907): Killing 4227:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,W/PluginManager( 4449): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,I/ActivityManager(  907): Recipient 4227
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/InputMethodManagerService(  907): Disable input method client, pid=4449
W/IInputConnectionWrapper( 4449): reportFullscreenMode on inactive InputConnection
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43b2f5d8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1180): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1180): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1180): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
,D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=9 entropy=4
,D/wpa_supplicant( 1180): Add randomness: count=10 entropy=5
D/wpa_supplicant( 1180): Add randomness: count=11 entropy=6
D/wpa_supplicant( 1180): Add randomness: count=12 entropy=7
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:48 type 0 added,
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
,I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1180): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000106514068
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000106514094
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000106514105,
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000106514119
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@435a7940 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@435a7940 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@435a7940 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 106514068, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 106514094, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 106514105, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 106514119, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4248
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4248:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4248
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(44314c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44314c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=3928
,I/ActivityManager(  907): Killing 3928:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3928
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4390f208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{41dcb868: PendingIntentRecord{424e2e28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=118498, Int=0
,D/PMS     (  907): releaseWL(4390f208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43ec3e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(431491d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(431491d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43ec3e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(442ea6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389,
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(442ea6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(438c3570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms},
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4337ff00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(433d8b90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1453367888401 tag=VacuumService
D/PMS     (  907): releaseWL(438c3570): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4337ff00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43e3afa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(43e3afa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42737ea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  907): releaseWL(433d8b90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(42737ea8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42c8c600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(42c8c600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43726728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(43726728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43655630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4338dd88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4338dd88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42590758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43655630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43eb1558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(43eb1558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 6344 seconds from now (1453367889215)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =fdea +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=50 [6][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(42590758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4391c538): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(4391c538): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(430ba6b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(430ba6b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=13 entropy=8
D/wpa_supplicant( 1180): Add randomness: count=14 entropy=9
D/wpa_supplicant( 1180): Add randomness: count=15 entropy=10
D/wpa_supplicant( 1180): Add randomness: count=16 entropy=11
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=17 entropy=12
D/wpa_supplicant( 1180): Add randomness: count=18 entropy=13
D/wpa_supplicant( 1180): Add randomness: count=19 entropy=14
D/wpa_supplicant( 1180): Add randomness: count=20 entropy=15
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 ,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000123602153
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g,
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56,
I/wpa_supplicant( 1180): tsf=0000000123602179
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
,I/wpa_supplicant( 1180): tsf=0000000123602189
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000123602199
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 123602153, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 123602179, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 123602189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 123602199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(435e17b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(435e17b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42463758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42463758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42424090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{43239548: PendingIntentRecord{427556f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135230, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  907): releaseWL(42424090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1313): service - handleMessage() stop self
,D/AutoSetting( 1313): service - handleMessage() quit looper
,D/AutoSetting( 1313): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4262
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4262:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4262
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=21 entropy=16
D/wpa_supplicant( 1180): Add randomness: count=22 entropy=17
D/wpa_supplicant( 1180): Add randomness: count=23 entropy=18
D/wpa_supplicant( 1180): Add randomness: count=24 entropy=19
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=25 entropy=20
D/wpa_supplicant( 1180): Add randomness: count=26 entropy=21
D/wpa_supplicant( 1180): Add randomness: count=27 entropy=22
D/wpa_supplicant( 1180): Add randomness: count=28 entropy=23
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
,I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000140954375
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000140954402
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000140954412
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
,I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000140954422
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 140954375, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 140954402, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 140954412, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 140954422, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(422c5f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42497bb0: PendingIntentRecord{42491698 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141471, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(4264f8e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(422c5f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =95e5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.,
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): releaseWL(4264f8e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=29 entropy=24
D/wpa_supplicant( 1180): Add randomness: count=30 entropy=25
D/wpa_supplicant( 1180): Add randomness: count=31 entropy=26
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=32 entropy=27
D/wpa_supplicant( 1180): Add randomness: count=33 entropy=28
D/wpa_supplicant( 1180): Add randomness: count=34 entropy=29
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000158354736
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000158354762
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000140954412
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000158354773
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 158354736, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 158354762, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 140954412, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 158354773, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(430edfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(430edfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44307578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{423f5028: PendingIntentRecord{42a8b338 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=170711, Int=0
,D/PMS     (  907): releaseWL(44307578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=35 entropy=30
D/wpa_supplicant( 1180): Add randomness: count=36 entropy=31
D/wpa_supplicant( 1180): Add randomness: count=37 entropy=32
D/wpa_supplicant( 1180): Add randomness: count=38 entropy=33
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL], c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=39 entropy=34
D/wpa_supplicant( 1180): Add randomness: count=40 entropy=35
D/wpa_supplicant( 1180): Add randomness: count=41 entropy=36
D/wpa_supplicant( 1180): Add randomness: count=42 entropy=37
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1,
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (523) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000175735279
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412,
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000175735306
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000175735317
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=4
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000175735326
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 175735279, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 175735306, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 175735317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 175735326, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == (4) end of scan result ==
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(430c7450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430c7450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=43 entropy=38
D/wpa_supplicant( 1180): Add randomness: count=44 entropy=39
D/wpa_supplicant( 1180): Add randomness: count=45 entropy=40
D/wpa_supplicant( 1180): Add randomness: count=46 entropy=41
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): ,[NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=47 entropy=42
D/wpa_supplicant( 1180): Add randomness: count=48 entropy=43
D/wpa_supplicant( 1180): Add randomness: count=49 entropy=44
D/wpa_supplicant( 1180): Add randomness: count=50 entropy=45
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (523) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000193094732
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000193094759
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000193094770
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=4
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000193094779
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 193094732, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 193094759, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 193094770, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 193094779, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56,
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=51 entropy=46
D/wpa_supplicant( 1180): Add randomness: count=52 entropy=47
D/wpa_supplicant( 1180): Add randomness: count=53 entropy=48
D/wpa_supplicant( 1180): Add randomness: count=54 entropy=49
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
,I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
,I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=55 entropy=50
D/wpa_supplicant( 1180): Add randomness: count=56 entropy=51
,D/wpa_supplicant( 1180): Add randomness: count=57 entropy=52
D/wpa_supplicant( 1180): Add randomness: count=58 entropy=53
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (523) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000210504972
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000210504998
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000210505009,
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=4
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000210505017
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 210504972, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 210504998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 210505009, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 210505017, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=59 entropy=54
D/wpa_supplicant( 1180): Add randomness: count=60 entropy=55
D/wpa_supplicant( 1180): Add randomness: count=61 entropy=56
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=62 entropy=57
D/wpa_supplicant( 1180): Add randomness: count=63 entropy=58
D/wpa_supplicant( 1180): Add randomness: count=64 entropy=59
D/wp,a_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (523) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000227895076
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
,I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000227895102
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000227895113
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=4
,I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000210505017
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 227895076, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 227895102, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 227895113, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 210505017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/PMS     (  907): acquireWL(43e63860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=230372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43e63860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=65 entropy=60
D/wpa_supplicant( 1180): Add randomness: count=66 entropy=61
D/wpa_supplicant( 1180): Add randomness: count=67 entropy=62
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=68 entropy=63
D/wpa_supplicant( 1180): Add randomness: count=69 entropy=64
D/wpa_supplicant( 1180): Add randomness: count=70 entropy=65
D/wp,a_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000245244934
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000245244959
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-84
I/wpa_supplicant( 1180): tsf=0000000245244970
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 245244934, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 245244959, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 245244970, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42f148d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42f148d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=71 entropy=66
D/wpa_supplicant( 1180): Add randomness: count=72 entropy=67
D/wpa_supplicant( 1180): Add randomness: count=73 entropy=68
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=74 entropy=69
D/wpa_supplicant( 1180): Add randomness: count=75 entropy=70
D/wpa_supplicant( 1180): Add randomness: count=76 entropy=71
D/wp,a_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
,I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000262614565
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000262614591
,I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-84
I/wpa_supplicant( 1180): tsf=0000000262614602
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 262614565, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 262614591, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 262614602, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=77 entropy=72
D/wpa_supplicant( 1180): Add randomness: count=78 entropy=73
D/wpa_supplicant( 1180): Add randomness: count=79 entropy=74
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=80 entropy=75
D/wpa_supplicant( 1180): Add randomness: count=81 entropy=76
D/wpa_supplicant( 1180): Add randomness: count=82 entropy=77
D/wp,a_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000279974858
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000279974884
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
,I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-84
I/wpa_supplicant( 1180): tsf=0000000279974896
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 279974858, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 279974884, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 279974896, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43567eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=290373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43567eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=83 entropy=78
D/wpa_supplicant( 1180): Add randomness: count=84 entropy=79
D/wpa_supplicant( 1180): Add randomness: count=85 entropy=80
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=86 entropy=81
D/wpa_supplicant( 1180): Add randomness: count=87 entropy=82
D/wpa_supplicant( 1180): Add randomness: count=88 entropy=83
D/wp,a_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000297374459
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000297374485
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000297374496
,I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 297374459, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 297374485, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 297374496, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43f36dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43f36dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available,
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results,
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=89 entropy=84
D/wpa_supplicant( 1180): Add randomness: count=90 entropy=85
D/wpa_supplicant( 1180): Add randomness: count=91 entropy=86
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
,I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
,D/wpa_supplicant( 1180): Add randomness: count=92 entropy=87
D/wpa_supplicant( 1180): Add randomness: count=93 entropy=88
D/wpa_supplicant( 1180): Add randomness: count=94 entropy=89
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000314723781
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000314723807
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====,
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000314723818
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 314723781, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 314723807, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 314723818, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter,
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=95 entropy=90
D/wpa_supplicant( 1180): Add randomness: count=96 entropy=91
D/wpa_supplicant( 1180): Add randomness: count=97 entropy=92
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=98 entropy=93
D/wpa_supplicant( 1180): Add randomness: count=99 entropy=94
D/wpa_supplicant( 1180): Add randomness: count=100 entropy=95
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000332104248
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000332104274
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000332104285
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
,I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 332104248, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 332104274, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 332104285, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=101 entropy=96
D/wpa_supplicant( 1180): Add randomness: count=102 entropy=97
D/wpa_supplicant( 1180): Add randomness: count=103 entropy=98
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=104 entropy=99
D/wpa_supplicant( 1180): Add randomness: count=105 entropy=100
D/wpa_supplicant( 1180): Add randomness: count=106 entropy=1,01
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000332104248
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000349465348
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000349465361
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 332104248, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 349465348, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 349465361, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42725058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=350373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42725058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=107 entropy=102
D/wpa_supplicant( 1180): Add randomness: count=108 entropy=103
D/wpa_supplicant( 1180): Add randomness: count=109 entropy=104
D/wpa_supplicant( 1180): Add randomness: count=110 entropy=105
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=111 entropy=106
D/wpa_supplicant( 1180): Add randomness: count=112 entropy=107
D/wpa_supplicant( 1180): Add randomness: count=113 entropy=108
D/wpa_supplicant( 1180): Add randomness: count=114 entropy=109
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000366845336
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412,
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000366845374
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000000366845384
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=5
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000366845362
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 366845336, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 366845374, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 366845384, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 366845362, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(438d94a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(438d94a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available,
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=115 entropy=110
D/wpa_supplicant( 1180): Add randomness: count=116 entropy=111
D/wpa_supplicant( 1180): Add randomness: count=117 entropy=112
D/wpa_supplicant( 1180): Add randomness: count=118 entropy=113
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
,I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
,D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=119 entropy=114
D/wpa_supplicant( 1180): Add randomness: count=120 entropy=115
D/wpa_supplicant( 1180): Add randomness: count=121 entropy=116
D/wpa_supplicant( 1180): Add randomness: count=122 entropy=117
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000384255046
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000384255083
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000000384255092
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=5
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000384255072
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 384255046, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 384255083, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 384255092, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 384255072, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=123 entropy=118
D/wpa_supplicant( 1180): Add randomness: count=124 entropy=119
D/wpa_supplicant( 1180): Add randomness: count=125 entropy=120
D/wpa_supplicant( 1180): Add randomness: count=126 entropy=121
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=127 entropy=122
D/wpa_supplicant( 1180): Add randomness: count=128 entropy=123
D/wpa_supplicant( 1180): Add randomness: count=129 entropy=124
D/wpa_supplicant( 1180): Add randomness: count=130 entropy=125
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000401634502
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000401634539
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000000401634549
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=5
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000401634528
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 401634502, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 401634539, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 401634549, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 401634528, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44349e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=410372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44349e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=131 entropy=126
D/wpa_supplicant( 1180): Add randomness: count=132 entropy=127
D/wpa_supplicant( 1180): Add randomness: count=133 entropy=128
D/wpa_supplicant( 1180): Add randomness: count=134 entropy=129
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=135 entropy=130
D/wpa_supplicant( 1180): Add randomness: count=136 entropy=131
D/wpa_supplicant( 1180): Add randomness: count=137 entropy=132
D/wpa_supplicant( 1180): Add randomness: count=138 entropy=133
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000419024658
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000419024695
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412,
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000419024705
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=5
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000419024684
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 419024658, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 419024695, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 419024705, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 419024684, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(430553d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430553d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=139 entropy=134
D/wpa_supplicant( 1180): Add randomness: count=140 entropy=135
D/wpa_supplicant( 1180): Add randomness: count=141 entropy=136
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=142 entropy=137
D/wpa_supplicant( 1180): Add randomness: count=143 entropy=138
D/wpa_supplicant( 1180): Add randomness: count=144 entro,py=139
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000436081981
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000436082006
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000436082017
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=5
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000419024684
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 436081981, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 436082006, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 436082017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 419024684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
,D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
,I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=145 entropy=140
D/wpa_supplicant( 1180): Add randomness: count=146 entropy=141
D/wpa_supplicant( 1180): Add randomness: count=147 entropy=142
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700',
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
,I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
,I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=148 entropy=143
D/wpa_supplicant( 1180): Add randomness: count=149 entropy=144
D/wpa_supplicant( 1180): Add randomness: count=150 entropy=145
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000453434573
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000453434599
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000453434610
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 453434573, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 453434599, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 453434610, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(44294460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=470373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44294460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=151 entropy=146
D/wpa_supplicant( 1180): Add randomness: count=152 entropy=147
D/wpa_supplicant( 1180): Add randomness: count=153 entropy=148
D/wpa_supplicant( 1180): Add randomness: count=154 entropy=149
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=155 entropy=150
D/wpa_supplicant( 1180): Add randomness: count=156 entropy=151
D/wpa_supplicant( 1180): Add randomness: count=157 entropy=152
D/wpa_supplicant( 1180): Add randomness: count=158 entropy=153
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000470854927
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====,
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000470854964
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000453434610
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6,
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000470854952
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 470854927, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 470854964, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 453434610, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 470854952, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=159 entropy=154
D/wpa_supplicant( 1180): Add randomness: count=160 entropy=155
D/wpa_supplicant( 1180): Add randomness: count=161 entropy=156
D/wpa_supplicant( 1180): Add randomness: count=162 entropy=157
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=163 entropy=158
D/wpa_supplicant( 1180): Add randomness: count=164 entropy=159
D/wpa_supplicant( 1180): Add randomness: count=165 entropy=160
D/wpa_supplicant( 1180): Add randomness: count=166 entropy=161
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000488214974
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g,
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000488215010
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000453434610
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000488214999
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC,
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 488214974, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 488215010, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 453434610, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 488214999, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==,
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4334cd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4334cd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=167 entropy=162
D/wpa_supplicant( 1180): Add randomness: count=168 entropy=163
D/wpa_supplicant( 1180): Add randomness: count=169 entropy=164
D/wpa_supplicant( 1180): Add randomness: count=170 entropy=165
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=171 entropy=166
D/wpa_supplicant( 1180): Add randomness: count=172 entropy=167
D/wpa_supplicant( 1180): Add randomness: count=173 entropy=168
D/wpa_supplicant( 1180): Add randomness: count=174 entropy=169
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000505635177
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000505635214
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000453434610
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000505635203
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 505635177, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 505635214, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 453434610, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 505635203, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=175 entropy=170
D/wpa_supplicant( 1180): Add randomness: count=176 entropy=171
D/wpa_supplicant( 1180): Add randomness: count=177 entropy=172
D/wpa_supplicant( 1180): Add randomness: count=178 entropy=173
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=179 entropy=174
D/wpa_supplicant( 1180): Add randomness: count=180 entropy=175
D/wpa_supplicant( 1180): Add randomness: count=181 entropy=176
D/wpa_supplicant( 1180): Add randomness: count=182 entropy=177
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000522984618
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
,I/wpa_supplicant( 1180): tsf=0000000522984655
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000453434610
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000522984644,
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 522984618, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 522984655, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 453434610, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 522984644, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(443c0040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=530372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(443c0040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=183 entropy=178
D/wpa_supplicant( 1180): Add randomness: count=184 entropy=179
D/wpa_supplicant( 1180): Add randomness: count=185 entropy=180
D/wpa_supplicant( 1180): Add randomness: count=186 entropy=181
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=187 entropy=182
D/wpa_supplicant( 1180): Add randomness: count=188 entropy=183
D/wpa_supplicant( 1180): Add randomness: count=189 entropy=184
D/wpa_supplicant( 1180): Add randomness: count=190 entropy=185
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000540375025
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000540375061
,I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000540375071
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000540375050
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 540375025, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 540375061, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 540375071, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 540375050, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(430faab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430faab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=191 entropy=186
D/wpa_supplicant( 1180): Add randomness: count=192 entropy=187
D/wpa_supplicant( 1180): Add randomness: count=193 entropy=188
D/wpa_supplicant( 1180): Add randomness: count=194 entropy=189
D/wpa_supplicant( 1180): Add randomness: count=195 entropy=190
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplican,t( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=196 entropy=191
D/wpa_supplicant( 1180): Add randomness: count=197 entropy=192
D/wpa_supplicant( 1180): Add randomness: count=198 entropy=193
D/wpa_supplicant( 1180): Add randomness: count=199 entropy=194
D/wpa_supplicant( 1180): Add randomness: count=200 entropy=195
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
,W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (636) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000557412129
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56,
I/wpa_supplicant( 1180): tsf=0000000557412166
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000557412176
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000557412155
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=7,
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000000557412185
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 557412129, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 557412166, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 557412176, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 557412155, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 557412185, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=201 entropy=196
D/wpa_supplicant( 1180): Add randomness: count=202 entropy=197
D/wpa_supplicant( 1180): Add randomness: count=203 entropy=198
D/wpa_supplicant( 1180): Add randomness: count=204 entropy=199
D/wpa_supplicant( 1180): Add randomness: count=205 entropy=200
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplican,t( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=206 entropy=201
D/wpa_supplicant( 1180): Add randomness: count=207 entropy=202
D/wpa_supplicant( 1180): Add randomness: count=208 entropy=203
D/wpa_supplicant( 1180): Add randomness: count=209 entropy=204
D/wpa_supplicant( 1180): Add randomness: count=210 entropy=205
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (636) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000574765430
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000574765466
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000574765476
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000574765456
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
,I/wpa_supplicant( 1180): id=7
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000000574765485
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 574765430, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 574765466, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 574765476, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 574765456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 574765485, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==,
,D/WifiStateMachine(  907): == (5) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(4434e230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=590373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4434e230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=211 entropy=206
D/wpa_supplicant( 1180): Add randomness: count=212 entropy=207
D/wpa_supplicant( 1180): Add randomness: count=213 entropy=208
D/wpa_supplicant( 1180): Add randomness: count=214 entropy=209
D/wpa_supplicant( 1180): Add randomness: count=215 entropy=210
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplican,t( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=216 entropy=211
D/wpa_supplicant( 1180): Add randomness: count=217 entropy=212
D/wpa_supplicant( 1180): Add randomness: count=218 entropy=213
D/wpa_supplicant( 1180): Add randomness: count=219 entropy=214
D/wpa_supplicant( 1180): Add randomness: count=220 entropy=215
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (636) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000592185414
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000592185451
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-84
I/wpa_supplicant( 1180): tsf=0000000592185461
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====,
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000592185440
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=7
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000000592185469
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 592185414, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 592185451, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 592185461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 592185440, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 592185469, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-92], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=221 entropy=216
D/wpa_supplicant( 1180): Add randomness: count=222 entropy=217
D/wpa_supplicant( 1180): Add randomness: count=223 entropy=218
D/wpa_supplicant( 1180): Add randomness: count=224 entropy=219
D/wpa_supplicant( 1180): Add randomness: count=225 entropy=220
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplican,t( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=226 entropy=221
D/wpa_supplicant( 1180): Add randomness: count=227 entropy=222
D/wpa_supplicant( 1180): Add randomness: count=228 entropy=223
D/wpa_supplicant( 1180): Add randomness: count=229 entropy=224
D/wpa_supplicant( 1180): Add randomness: count=230 entropy=225
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (636) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000592185414
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000609565042
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-84
I/wpa_supplicant( 1180): tsf=0000000609565063
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000609565053
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=7
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000609565073
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 592185414, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 609565042, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 609565063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 609565053, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 609565073, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42eb5d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42eb5d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1239): sku_id=99
D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=231 entropy=226
D/wpa_supplicant( 1180): Add randomness: count=232 entropy=227
D/wpa_supplicant( 1180): Add randomness: count=233 entropy=228
D/wpa_supplicant( 1180): Add randomness: count=234 entropy=229
D/wpa_supplicant( 1180): Add randomness: count=235 entropy=230
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplican,t( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=236 entropy=231
D/wpa_supplicant( 1180): Add randomness: count=237 entropy=232
D/wpa_supplicant( 1180): Add randomness: count=238 entropy=233
D/wpa_supplicant( 1180): Add randomness: count=239 entropy=234
D/wpa_supplicant( 1180): Add randomness: count=240 entropy=235
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (636) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000626915002
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000626915039
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-84
I/wpa_supplicant( 1180): tsf=0000000626915048
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000626915028
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=7,
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000626915057
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 626915002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 626915039, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 626915048, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 626915028, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 626915057, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/Process (  907): killProcessQuiet, pid=4037
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4037:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4037
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS,
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=241 entropy=236
D/wpa_supplicant( 1180): Add randomness: count=242 entropy=237
D/wpa_supplicant( 1180): Add randomness: count=243 entropy=238
D/wpa_supplicant( 1180): Add randomness: count=244 entropy=239
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=245 entropy=240
D/wpa_supplicant( 1180): Add randomness: count=246 entropy=241
D/wpa_supplicant( 1180): Add randomness: count=247 entropy=242
,D/wpa_supplicant( 1180): Add randomness: count=248 entropy=243
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (636) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000644324878
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000644324915
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
,I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-84
I/wpa_supplicant( 1180): tsf=0000000626915048
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000644324904
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=7
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000644324924
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 644324878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 644324915, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 626915048, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 644324904, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 644324924, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426658a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=650373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  907): releaseWL(426658a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=249 entropy=244
D/wpa_supplicant( 1180): Add randomness: count=250 entropy=245
D/wpa_supplicant( 1180): Add randomness: count=251 entropy=246
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): Add randomness: count=252 entropy=247
D/wpa_supplicant( 1180): Add random,ness: count=253 entropy=248
D/wpa_supplicant( 1180): Add randomness: count=254 entropy=249
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (636) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000661704668
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1,
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000661704689
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000661704698
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=6
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000644324904
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=7
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000644324924
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 661704668, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 661704689, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 661704698, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 644324904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 644324924, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42782d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42782d98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=255 entropy=250
D/wpa_supplicant( 1180): Add randomness: count=256 entropy=251
D/wpa_supplicant( 1180): Add randomness: count=257 entropy=252
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=258 entropy=253
D/wpa_supplicant( 1180): Add randomness: count=259 entropy=254
D/wpa_supplicant( 1180): Add randomness: count=260 entro,py=255
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000661704668
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000679094006
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
,I/wpa_supplicant( 1180): tsf=0000000679094017
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 661704668, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 679094006, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 679094017, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=261 entropy=256
D/wpa_supplicant( 1180): Add randomness: count=262 entropy=257
D/wpa_supplicant( 1180): Add randomness: count=263 entropy=258
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=264 entropy=259
D/wpa_supplicant( 1180): Add randomness: count=265 entropy=260
D/wpa_supplicant( 1180): Add randomness: count=266 entro,py=261
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000696474710
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000696474736
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000696474746
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 696474710, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 696474736, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 696474746, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426b4680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=710373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426b4680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=267 entropy=262
D/wpa_supplicant( 1180): Add randomness: count=268 entropy=263
D/wpa_supplicant( 1180): Add randomness: count=269 entropy=264
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=270 entropy=265
D/wpa_supplicant( 1180): Add randomness: count=271 entropy=266
D/wpa_supplicant( 1180): Add randomness: count=272 entro,py=267
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000713854810
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000713854838
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
,I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000713854850
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 713854810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 713854838, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 713854850, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=273 entropy=268
D/wpa_supplicant( 1180): Add randomness: count=274 entropy=269
D/wpa_supplicant( 1180): Add randomness: count=275 entropy=270
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=276 entropy=271
D/wpa_supplicant( 1180): Add randomness: count=277 entropy=272
D/wpa_supplicant( 1180): Add randomness: count=278 entro,py=273
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
,W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000731274631
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000731274657
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000731274668
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####,
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 731274631, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 731274657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 731274668, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/PMS     (  907): acquireWL(43edaf88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end,
,D/PMS     (  907): releaseWL(43edaf88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=279 entropy=274
D/wpa_supplicant( 1180): Add randomness: count=280 entropy=275
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=281 entropy=276
D/wpa_supplicant( 1180): Add randomness: count=282 entropy=277
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA ,subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000748634074
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000748634100
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
,I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000731274668
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 748634074, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 748634100, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 731274668, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=283 entropy=278
D/wpa_supplicant( 1180): Add randomness: count=284 entropy=279
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
,D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=285 entropy=280
D/wpa_supplicant( 1180): Add randomness: count=286 entropy=281
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (238) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
,I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000766034474
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000766034501
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 766034474, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 766034501, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 2 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): == begin of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (2) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42c43b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=770373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42c43b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=287 entropy=282
D/wpa_supplicant( 1180): Add randomness: count=288 entropy=283
D/wpa_supplicant( 1180): Add randomness: count=289 entropy=284
D/wpa_supplicant( 1180): Add randomness: count=290 entropy=285
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant(, 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-87
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=291 entropy=286
D/wpa_supplicant( 1180): Add randomness: count=292 entropy=287
D/wpa_supplicant( 1180): Add randomness: count=293 entropy=288
D/wpa_supplicant( 1180): Add randomness: count=294 entropy=289
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (523) for get BSS: id=0,
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000783465000
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
,I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000783465025
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-87
I/wpa_supplicant( 1180): tsf=0000000783465035
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
,I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=9
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000783465046
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 783465000, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 783465025, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2412, timestamp: 783465035, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 783465046, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-87], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(436c6e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(436c6e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=295 entropy=290
D/wpa_supplicant( 1180): Add randomness: count=296 entropy=291
D/wpa_supplicant( 1180): Add randomness: count=297 entropy=292
D/wpa_supplicant( 1180): Add randomness: count=298 entropy=293
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant(, 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=299 entropy=294
D/wpa_supplicant( 1180): Add randomness: count=300 entropy=295
D/wpa_supplicant( 1180): Add randomness: count=301 entropy=296
D/wpa_supplicant( 1180): Add randomness: count=302 entropy=297
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (523) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000800824084
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g,
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000800824109
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-79
I/wpa_supplicant( 1180): tsf=0000000783465035
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=9
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e,
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000800824130
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 800824084, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 800824109, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 783465035, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 800824130, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS,
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
,I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=303 entropy=298
D/wpa_supplicant( 1180): Add randomness: count=304 entropy=299
D/wpa_supplicant( 1180): Add randomness: count=305 entropy=300
D/wpa_supplicant( 1180): Add randomness: count=306 entropy=301
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
,D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
,I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
,W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=307 entropy=302
,D/wpa_supplicant( 1180): Add randomness: count=308 entropy=303
D/wpa_supplicant( 1180): Add randomness: count=309 entropy=304
D/wpa_supplicant( 1180): Add randomness: count=310 entropy=305
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (523) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000818174990
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000818175016
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-79,
I/wpa_supplicant( 1180): tsf=0000000783465035
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=9
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000818175037
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 818174990, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 818175016, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 783465035, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 818175037, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44331c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=830372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44331c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=311 entropy=306
D/wpa_supplicant( 1180): Add randomness: count=312 entropy=307
D/wpa_supplicant( 1180): Add randomness: count=313 entropy=308
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=314 entropy=309
D/wpa_supplicant( 1180): Add randomness: count=315 entropy=310
D/wpa_supplicant( 1180): Add randomness: count=316 entro,py=311
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (523) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46,
I/wpa_supplicant( 1180): tsf=0000000835504713
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000835504739
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-79
I/wpa_supplicant( 1180): tsf=0000000783465035
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=9
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000000818175037
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 835504713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 835504739, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 783465035, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 818175037, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter,
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(442a83f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(442a83f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=317 entropy=312
D/wpa_supplicant( 1180): Add randomness: count=318 entropy=313
D/wpa_supplicant( 1180): Add randomness: count=319 entropy=314
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=320 entropy=315
D/wpa_supplicant( 1180): Add randomness: count=321 entropy=316
D/wpa_supplicant( 1180): Add randomness: count=322 entro,py=317
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000852885384
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000852885410
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-86
I/wpa_supplicant( 1180): tsf=0000000852885420
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 852885384, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 852885410, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 852885420, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS,
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=323 entropy=318,
D/wpa_supplicant( 1180): Add randomness: count=324 entropy=319
D/wpa_supplicant( 1180): Add randomness: count=325 entropy=320
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available,
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
,I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
,I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
,I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
,I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=326 entropy=321
D/wpa_supplicant( 1180): Add randomness: count=327 entropy=322
D/wpa_supplicant( 1180): Add randomness: count=328 entropy=323
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000870304862
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
,I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000870304888
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
,I/wpa_supplicant( 1180): level=-86
I/wpa_supplicant( 1180): tsf=0000000870304899
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 870304862, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 870304888, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 870304899, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter,
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=329 entropy=324
D/wpa_supplicant( 1180): Add randomness: count=330 entropy=325
D/wpa_supplicant( 1180): Add randomness: count=331 entropy=326
D/wpa_supplicant( 1180): Add randomness: count=332 entropy=327
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=333 entropy=328
D/wpa_supplicant( 1180): Add randomness: count=334 entropy=329
D/wpa_supplicant( 1180): Add randomness: count=335 entropy=330
D/wpa_supplicant( 1180): Add randomness: count=336 entropy=331
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (490) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000887714975
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1,
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000887715012
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000887715022
,I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=10
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000887715000
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 887714975, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 887715012, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 887715022, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 887715000, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(43b7ae50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=890372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43b7ae50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=337 entropy=332
D/wpa_supplicant( 1180): Add randomness: count=338 entropy=333
D/wpa_supplicant( 1180): Add randomness: count=339 entropy=334
D/wpa_supplicant( 1180): Add randomness: count=340 entropy=335
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=341 entropy=336
D/wpa_supplicant( 1180): Add randomness: count=342 entropy=337
D/wpa_supplicant( 1180): Add randomness: count=343 entropy=338
D/wpa_supplicant( 1180): Add randomness: count=344 entropy=339
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (490) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000905084939
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000905084978
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000905084988
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=10
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000905084965
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 905084939, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 905084978, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 905084988, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 905084965, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/PMS     (  907): acquireWL(426608b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(426608b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b26a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b26a20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=345 entropy=340
D/wpa_supplicant( 1180): Add randomness: count=346 entropy=341
D/wpa_supplicant( 1180): Add randomness: count=347 entropy=342
D/wpa_supplicant( 1180): Add randomness: count=348 entropy=343
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_sup,plicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=349 entropy=344
D/wpa_supplicant( 1180): Add randomness: count=350 entropy=345
D/wpa_supplicant( 1180): Add randomness: count=351 entropy=346
D/wpa_supplicant( 1180): Add randomness: count=352 entropy=347
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (490) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000922495003
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000922495040
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000922495049
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=10
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000922495029
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 922495003, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 922495040, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 922495049, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 922495029, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=353 entropy=348
D/wpa_supplicant( 1180): Add randomness: count=354 entropy=349
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=355 entropy=350
D/wpa_supplicant( 1180): Add randomness: count=356 entropy=351
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] ,enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (490) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000939844780
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000939844805
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000000922495049
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=10
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000000922495029
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 939844780, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): InactiveState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 939844805, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): P2pEnabledState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 922495049, distance: ?(cm), distanceSd: ?(cm),
D/WifiP2pService(  907): DefaultState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 922495029, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43167520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41dc2a90: PendingIntentRecord{424c2350 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=778858, Int=0
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{42779218: PendingIntentRecord{4267d710 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=945268, Int=0
,D/PMS     (  907): acquireWL(4317afd8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4317afd8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4555 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4263c1b0: PendingIntentRecord{426be200 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453367981316, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{43eedef0: PendingIntentRecord{4267b128 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453368160699, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{424cdbc8: PendingIntentRecord{424675c8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453368701831, Int=900000
,D/PMS     (  907): acquireWL(44184cb0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2161 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(4431c440): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2161 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44184cb0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4504): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4504): MY_DEBUG = false
D/PMS     (  907): releaseWL(43167520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4555/10049)
,I/EventLogService( 2161): Aggregate from 1453367820319 (log), 1453366360653 (data)
W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(4431c440): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=3470
,I/ActivityManager(  907): Killing 3470:com.android.defcontainer/u0a19 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3470
,D/PMS     (  907): acquireWL(420d9ad0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023742
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024038
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024086
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024090
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024094
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024099
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025374
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025389
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028146
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029766
,D/PMS     (  907): releaseWL(420d9ad0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425daf58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=950373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425daf58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=357 entropy=352
D/wpa_supplicant( 1180): Add randomness: count=358 entropy=353
D/wpa_supplicant( 1180): Add randomness: count=359 entropy=354
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=360 entropy=355
D/wpa_supplicant( 1180): Add randomness: count=361 entropy=356
D/wpa_supplicant( 1180): Add randomness: count=362 entro,py=357
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
,I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000957234757
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000957234784
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000957234796
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 957234757, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 957234784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 957234796, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4355e6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/PowerUI ( 1114): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(4355e6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(426ac9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  907): releaseWL(426ac9b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=363 entropy=358
D/wpa_supplicant( 1180): Add randomness: count=364 entropy=359
D/wpa_supplicant( 1180): Add randomness: count=365 entropy=360
D/wpa_supplicant( 1180): Add randomness: count=366 entropy=361
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sort,ed scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=367 entropy=362
D/wpa_supplicant( 1180): Add randomness: count=368 entropy=363
D/wpa_supplicant( 1180): Add randomness: count=369 entropy=364
D/wpa_supplicant( 1180): Add randomness: count=370 entropy=365
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (506) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000974644885
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000974644911
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000974644922
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=11
I/wpa_supplicant( 1180): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1180): freq=2462
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000000974644933
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 974644885, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 974644911, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 974644922, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -92, frequency: 2462, timestamp: 974644933, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=371 entropy=366
D/wpa_supplicant( 1180): Add randomness: count=372 entropy=367
D/wpa_supplicant( 1180): Add randomness: count=373 entropy=368
D/wpa_supplicant( 1180): Add randomness: count=374 entropy=369
D/wpa_supplicant( 1180): Add randomness: count=375 entropy=370
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 11,80): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=376 entropy=371
D/wpa_supplicant( 1180): Add randomness: count=377 entropy=372
D/wpa_supplicant( 1180): Add randomness: count=378 entropy=373
D/wpa_supplicant( 1180): Add randomness: count=379 entropy=374
D/wpa_supplicant( 1180): Add randomness: count=380 entropy=375
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (654) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000992034764
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000992034790
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000992034801
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=11
I/wpa_supplicant( 1180): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1180): freq=2462
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000000992034821,
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=12
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-93
I/wpa_supplicant( 1180): tsf=0000000992034809
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 992034764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 992034790, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 992034801, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -92, frequency: 2462, timestamp: 992034821, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 992034809, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43373500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/SmartSyncUtils( 4504): isEpsOn(), nState = 0
V/AlarmManager(  907): sending alarm PendingIntent{4259c2a8: PendingIntentRecord{43f10558 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453368774792, Int=0
D/PMS     (  907): releaseWL(43373500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  907): acquireWL(43f33540): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4504 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4504): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4504): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4504): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4504): SettingOnTime = 1453442400000, randomSettingOnTime = 1453440087000
,D/SmartSyncScreenOnOffTimeReceiver( 4504): SettingOffTime = 1453428000000, randomSettingOffTime = 1453431485000
,D/SmartSyncScreenOnOffTimeReceiver( 4504): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4504): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4504): bNightModeTurnOffOnce = false
,D/PMS     (  907): releaseWL(43f33540): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=381 entropy=376
D/wpa_supplicant( 1180): Add randomness: count=382 entropy=377
D/wpa_supplicant( 1180): Add randomness: count=383 entropy=378
D/wpa_supplicant( 1180): Add randomness: count=384 entropy=379
D/wpa_supplicant( 1180): Add randomness: count=385 entropy=380
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 0c:bd:51:2b:c1:25 ssid='PLAY-ONLINE_1167' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 11,80): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-92
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=386 entropy=381
D/wpa_supplicant( 1180): Add randomness: count=387 entropy=382
D/wpa_supplicant( 1180): Add randomness: count=388 entropy=383
D/wpa_supplicant( 1180): Add randomness: count=389 entropy=384
D/wpa_supplicant( 1180): Add randomness: count=390 entropy=385
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (654) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000992034764
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412,
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001009172743
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000992034801
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=11
I/wpa_supplicant( 1180): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1180): freq=2462
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000001009172772
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=12
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-93
I/wpa_supplicant( 1180): tsf=0000000992034809
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 992034764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1009172743, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 992034801, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -92, frequency: 2462, timestamp: 1009172772, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 992034809, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/PMS     (  907): acquireWL(437d2b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1010373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437d2b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=391 entropy=386
D/wpa_supplicant( 1180): Add randomness: count=392 entropy=387
D/wpa_supplicant( 1180): Add randomness: count=393 entropy=388
D/wpa_supplicant( 1180): Add randomness: count=394 entropy=389
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a fre,q=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=395 entropy=390
D/wpa_supplicant( 1180): Add randomness: count=396 entropy=391
D/wpa_supplicant( 1180): Add randomness: count=397 entropy=392
D/wpa_supplicant( 1180): Add randomness: count=398 entropy=393
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (654) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001026524522
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g,
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001026524548
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000000992034801
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=11
I/wpa_supplicant( 1180): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1180): freq=2462
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000001009172772
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1180): ====,
I/wpa_supplicant( 1180): id=12
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-93
I/wpa_supplicant( 1180): tsf=0000000992034809
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1026524522, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1026524548, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 992034801, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -92, frequency: 2462, timestamp: 1009172772, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 992034809, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                 PLAY-ONLINE_1167 [0c:bd:51:2b:c1:25], Rssi:  0 [-92], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43b630e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b630e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=399 entropy=394
D/wpa_supplicant( 1180): Add randomness: count=400 entropy=395
D/wpa_supplicant( 1180): Add randomness: count=401 entropy=396
D/wpa_supplicant( 1180): Add randomness: count=402 entropy=397
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a fre,q=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=403 entropy=398
D/wpa_supplicant( 1180): Add randomness: count=404 entropy=399
D/wpa_supplicant( 1180): Add randomness: count=405 entropy=400
D/wpa_supplicant( 1180): Add randomness: count=406 entropy=401
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (524) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
,I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001043944867
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001043944893
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-85
I/wpa_supplicant( 1180): tsf=0000001043944904
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=12
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-93
I/wpa_supplicant( 1180): tsf=0000000992034809
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1043944867, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1043944893, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 1043944904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 992034809, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1180): nl80211: Event message available,
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=407 entropy=402,
D/wpa_supplicant( 1180): Add randomness: count=408 entropy=403
D/wpa_supplicant( 1180): Add randomness: count=409 entropy=404
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
,I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
,I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-86
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=410 entropy=405
D/wpa_supplicant( 1180): Add randomness: count=411 entropy=406
D/wpa_supplicant( 1180): Add randomness: count=412 entropy=407
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (524) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001043944867
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001061354984
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
,I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-86,
I/wpa_supplicant( 1180): tsf=0000001043944904
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=12
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-93
I/wpa_supplicant( 1180): tsf=0000000992034809
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1043944867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1061354984, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2412, timestamp: 1043944904, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-86], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 992034809, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(442a5180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1070373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(442a5180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=413 entropy=408
D/wpa_supplicant( 1180): Add randomness: count=414 entropy=409
D/wpa_supplicant( 1180): Add randomness: count=415 entropy=410
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=416 entropy=411
D/wpa_supplica,nt( 1180): Add randomness: count=417 entropy=412
D/wpa_supplicant( 1180): Add randomness: count=418 entropy=413
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220,
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001043944867
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001078764098
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-78
I/wpa_supplicant( 1180): tsf=0000001043944904
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
,I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1043944867, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1078764098, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 1043944904, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1222): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(41e24200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(41e24200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1180): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=419 entropy=414
D/wpa_supplicant( 1180): Add randomness: count=420 entropy=415
D/wpa_supplicant( 1180): Add randomness: count=421 entropy=416
D/wpa_supplicant( 1180): Add randomness: count=422 entropy=417
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:,d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1180): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=423 entropy=418
D/wpa_supplicant( 1180): Add randomness: count=424 entropy=419
D/wpa_supplicant( 1180): Add randomness: count=425 entropy=420
D/wpa_supplicant( 1180): Add randomness: count=426 entropy=421
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (520) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001095872488
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
,I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001095872515
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000001095872526
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=13
I/wpa_supplicant( 1180): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-90
I/wpa_supplicant( 1180): tsf=0000001095872535
I/wpa_supplicant( 1180): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=UPC Wi-Free
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1095872488, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1095872515, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1095872526, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 1095872535, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1180): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=427 entropy=422
D/wpa_supplicant( 1180): Add randomness: count=428 entropy=423
D/wpa_supplicant( 1180): Add randomness: count=429 entropy=424
D/wpa_supplicant( 1180): Add randomness: count=430 entropy=425
D/wpa_supplicant( 1180): Add randomness: count=431 entropy=426
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 11,80): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1180): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=432 entropy=427
D/wpa_supplicant( 1180): Add randomness: count=433 entropy=428
D/wpa_supplicant( 1180): Add randomness: count=434 entropy=429
D/wpa_supplicant( 1180): Add randomness: count=435 entropy=430
D/wpa_supplicant( 1180): Add randomness: count=436 entropy=431
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (634) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001095872488
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001113274787
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000001113274797
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=13
I/wpa_supplicant( 1180): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-90
I/wpa_supplicant( 1180): tsf=0000001113274806
I/wpa_supplicant( 1180): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=UPC Wi-Free
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=14
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001113274775
,I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1095872488, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1113274787, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1113274797, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 1113274806, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1113274775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(44221cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1130372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44221cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1180): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=437 entropy=432
D/wpa_supplicant( 1180): Add randomness: count=438 entropy=433
D/wpa_supplicant( 1180): Add randomness: count=439 entropy=434
D/wpa_supplicant( 1180): Add randomness: count=440 entropy=435
D/wpa_supplicant( 1180): Add randomness: count=441 entropy=436
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 11,80): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
I/wpa_supplicant( 1180): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-90
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=442 entropy=437
D/wpa_supplicant( 1180): Add randomness: count=443 entropy=438
D/wpa_supplicant( 1180): Add randomness: count=444 entropy=439
D/wpa_supplicant( 1180): Add randomness: count=445 entropy=440
D/wpa_supplicant( 1180): Add randomness: count=446 entropy=441
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (634) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001130655204
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001130655241
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000001130655251
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=13
I/wpa_supplicant( 1180): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-90
I/wpa_supplicant( 1180): tsf=0000001130655259
I/wpa_supplicant( 1180): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=UPC Wi-Free
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=14
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001130655230
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1130655204, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1130655241, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1130655251, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 1130655259, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1130655230, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56,
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=447 entropy=442
D/wpa_supplicant( 1180): Add randomness: count=448 entropy=443
D/wpa_supplicant( 1180): Add randomness: count=449 entropy=444
D/wpa_supplicant( 1180): Add randomness: count=450 entropy=445
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
,I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=451 entropy=446
D/wpa_supplicant( 1180): Add randomness: count=452 entropy=447
D/wpa_supplicant( 1180): Add randomness: count=453 entropy=448
D/wpa_supplicant( 1180): Add randomness: count=454 entropy=449
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1180): reply (634) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001148015095
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001148015133
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000001148015143
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
,I/wpa_supplicant( 1180): id=13
I/wpa_supplicant( 1180): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-90
I/wpa_supplicant( 1180): tsf=0000001130655259
I/wpa_supplicant( 1180): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=UPC Wi-Free
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=14
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001148015122
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1148015095, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1148015133, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1148015143, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2437, timestamp: 1130655259, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1148015122, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  0 [-90], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4378eb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(4378eb20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=455 entropy=450
D/wpa_supplicant( 1180): Add randomness: count=456 entropy=451
D/wpa_supplicant( 1180): Add randomness: count=457 entropy=452
D/wpa_supplicant( 1180): Add randomness: count=458 entropy=453
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=459 entropy=454
D/wpa_supplicant( 1180): Add randomness: count=460 entropy=455
D/wpa_supplicant( 1180): Add randomness: count=461 entropy=456
D/wpa_supplicant( 1180): Add randomness: count=462 entropy=457
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (490) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001165414874
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001165414911
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-77
I/wpa_supplicant( 1180): tsf=0000001165414921
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=14
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001165414900
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1165414874, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1165414911, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 1165414921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1165414900, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=463 entropy=458
D/wpa_supplicant( 1180): Add randomness: count=464 entropy=459
D/wpa_supplicant( 1180): Add randomness: count=465 entropy=460
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=466 entropy=461
D/wpa_supplica,nt( 1180): Add randomness: count=467 entropy=462
D/wpa_supplicant( 1180): Add randomness: count=468 entropy=463
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (490) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001182795059
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
,I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001182795084
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000001182795095
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=14
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001165414900
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1182795059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1182795084, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1182795095, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1165414900, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42eac848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1190372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42eac848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=469 entropy=464
D/wpa_supplicant( 1180): Add randomness: count=470 entropy=465
D/wpa_supplicant( 1180): Add randomness: count=471 entropy=466
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=472 entropy=467
D/wpa_supplica,nt( 1180): Add randomness: count=473 entropy=468
D/wpa_supplicant( 1180): Add randomness: count=474 entropy=469
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001200184677
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001200184703
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000001200184716
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1200184677, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1200184703, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1200184716, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(442c88c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(442c88c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=475 entropy=470
D/wpa_supplicant( 1180): Add randomness: count=476 entropy=471
D/wpa_supplicant( 1180): Add randomness: count=477 entropy=472
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplica,nt( 1180): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=478 entropy=473
D/wpa_supplicant( 1180): Add randomness: count=479 entropy=474
D/wpa_supplicant( 1180): Add randomness: count=480 entropy=475
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (376) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001217242209
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001217242235
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000001217242246
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, freque,ncy: 5220, timestamp: 1217242209, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1217242235, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1217242246, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=481 entropy=476
D/wpa_supplicant( 1180): Add randomness: count=482 entropy=477
D/wpa_supplicant( 1180): Add randomness: count=483 entropy=478
D/wpa_supplicant( 1180): Add randomness: count=484 entropy=479
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:a,a:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-76
D/wpa_supplicant( 1180): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=485 entropy=480
D/wpa_supplicant( 1180): Add randomness: count=486 entropy=481
D/wpa_supplicant( 1180): Add randomness: count=487 entropy=482
D/wpa_supplicant( 1180): Add randomness: count=488 entropy=483
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (490) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001234624888
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001234624927
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-76
I/wpa_supplicant( 1180): tsf=0000001234624937
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=15
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001234624915
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1234624888, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1234624927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2412, timestamp: 1234624937, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1234624915, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(43f065f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1250373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43f065f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1180): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=489 entropy=484
D/wpa_supplicant( 1180): Add randomness: count=490 entropy=485
D/wpa_supplicant( 1180): Add randomness: count=491 entropy=486
D/wpa_supplicant( 1180): Add randomness: count=492 entropy=487
D/wpa_supplicant( 1180): Add randomness: count=493 entropy=488
D/wpa_supplicant( 1180): Add randomness: count=494 entropy=489
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wa,pi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1180): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=495 entropy=490
D/wpa_supplicant( 1180): Add randomness: count=496 entropy=491
D/wpa_supplicant( 1180): Add randomness: count=497 entropy=492
D/wpa_supplicant( 1180): Add randomness: count=498 entropy=493
D/wpa_supplicant( 1180): Add randomness: count=499 entropy=494
D/wpa_supplicant( 1180): Add randomness: count=500 entropy=495
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (786) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001252065515
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56,
I/wpa_supplicant( 1180): tsf=0000001252065552
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-85
I/wpa_supplicant( 1180): tsf=0000001252065563
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=15
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001252065541
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=16
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000001252065571
,I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=17
I/wpa_supplicant( 1180): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000001252065582
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC5999698
I/wpa_supplicant( 1180): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1252065515, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1252065552, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 1252065563, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1252065541, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1252065571, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 1252065582, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1222): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1180): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=501 entropy=496
D/wpa_supplicant( 1180): Add randomness: count=502 entropy=497
D/wpa_supplicant( 1180): Add randomness: count=503 entropy=498
D/wpa_supplicant( 1180): Add randomness: count=504 entropy=499
D/wpa_supplicant( 1180): Add randomness: count=505 entropy=500
D/wpa_supplicant( 1180): Add randomness: count=506 entropy=501
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 5: 64:7c:34:12:7,f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1180): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=507 entropy=502
D/wpa_supplicant( 1180): Add randomness: count=508 entropy=503
D/wpa_supplicant( 1180): Add randomness: count=509 entropy=504
D/wpa_supplicant( 1180): Add randomness: count=510 entropy=505
D/wpa_supplicant( 1180): Add randomness: count=511 entropy=506
D/wpa_supplicant( 1180): Add randomness: count=512 entropy=507
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (786) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001269415080
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001269415117
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
,I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-85
I/wpa_supplicant( 1180): tsf=0000001269415127
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=15
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001269415106
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=16
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000001269415136
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=17
I/wpa_supplicant( 1180): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000001269415146
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC5999698
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1269415080, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1269415117, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 1269415127, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1269415106, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1269415136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 1269415146, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44529af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
D/PMS     (  907): releaseWL(44529af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1180): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/wpa_supplicant( 1180): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=513 entropy=508
D/wpa_supplicant( 1180): Add randomness: count=514 entropy=509
D/wpa_supplicant( 1180): Add randomness: count=515 entropy=510
D/wpa_supplicant( 1180): Add randomness: count=516 entropy=511
D/wpa_supplicant( 1180): Add randomness: count=517 entropy=512
D/wpa_supplicant( 1180): Add randomness: count=518 entropy=513
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1180): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1180): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 4: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1180): 5: 64:7c:34:12:7,f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1180): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1180): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1180): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-92
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1180): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=519 entropy=514
D/wpa_supplicant( 1180): Add randomness: count=520 entropy=515
D/wpa_supplicant( 1180): Add randomness: count=521 entropy=516
D/wpa_supplicant( 1180): Add randomness: count=522 entropy=517
D/wpa_supplicant( 1180): Add randomness: count=523 entropy=518
D/wpa_supplicant( 1180): Add randomness: count=524 entropy=519
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/,wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (786) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001286774484
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001286774521
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-85
I/wpa_supplicant( 1180): tsf=0000001286774532
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=15
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001286774510
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=16
I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000001286774541
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=17
I/wpa_supplicant( 1180): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000001286774552
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC5999698
I/wpa_supplicant( 1180): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1286774484, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1286774521, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 1286774532, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1286774510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1286774541, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 1286774552, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=525 entropy=520
D/wpa_supplicant( 1180): Add randomness: count=526 entropy=521
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 9
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 0
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=527 entropy=522
D/wpa_supplicant( 1180): Add randomness: count=528 entropy=523
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 ,len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1180): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1180): reply (786) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000001304132189
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1,
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000001304132215
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=8
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-85
I/wpa_supplicant( 1180): tsf=0000001286774532
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=15
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-55
I/wpa_supplicant( 1180): tsf=0000001286774510
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=16
,I/wpa_supplicant( 1180): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-91
I/wpa_supplicant( 1180): tsf=0000001286774541
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC4688432
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=17
I/wpa_supplicant( 1180): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1180): freq=2437
I/wpa_supplicant( 1180): level=-92
I/wpa_supplicant( 1180): tsf=0000001286774552
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=UPC5999698
I/wpa_supplicant( 1180): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 1304132189, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 1304132215, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 1286774532, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1286774510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 1286774541, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 1286774552, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  0 [-92], Tx: 13, Freq:  8 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4247aa98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4205ea18: PendingIntentRecord{41e5aad0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1310373, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4247aa98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4579): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4579): ====startRecUseTime====
D/htc.customization.log.level( 4579):  is 
W/CustomizationLogLevel( 4579): Level value is invalid, use default level 2
D/CustomizationManager( 4579):  Read ACC file spent 0.098 (s)
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4579): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4579): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4579): Parsing tag category name = system
I/CustomizationCIDLoader( 4579): Parsing tag category name = application
I/CustomizationCIDLoader( 4579): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4579): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4579): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4579): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4579): Parsing tag category name = Settings
D/CustomizationManager( 4579):  Read CID file spent 0.135 (s)
D/CustomizationManager( 4579):  All configurations done spent 0.135 (s)
W/HtcNativeFlag( 4579): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4579): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4579): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4579): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4579, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=4449
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 4449:com.test.thalitest/u0a389 (adj 11): stop com.test.thalitest
W/asset   (  907): Copying FileAsset 0x627d6b78 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  907): Skipping PackageSetting{4220db98 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(42eac3c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42eac3c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1337): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Scheme: "smsto"
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1337): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1337): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Scheme: "mms"
I/[PluginManager]RegisterService( 1313): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1313): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/IcingCorporaProvider( 2866): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1337): Unsupported attribute readOnly
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4594 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(4250e570): PARTIAL_WAKE_LOCK  Icing 0x1 2161 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4250e570): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4594): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(423fe9b8): PARTIAL_WAKE_LOCK  Icing 0x1 2161 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4607 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/IcingCorporaProvider( 2866): UpdateCorporaTask done [took 513 ms] updated apps [took 513 ms] 
D/AppTag  ( 4607): getInstance(Context context)
D/AppTag  ( 4607): getInstance(Context context)
D/AppTag  ( 4607): onCreate()
D/PMS     (  907): acquireWL(42f12660): PARTIAL_WAKE_LOCK  AsyncService 0x1 3605 10160 null
D/PMS     (  907): releaseWL(42f12660): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4079): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2161): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2161): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2161): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2161): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2161): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2161): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2161): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2161): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2161): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2161): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65388930
E/SQLiteDBG( 2161): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65a4f1b8
W/dalvikvm( 2161): threadid=49: thread exiting with uncaught exception (group=0x416fee30)
E/DriveAsyncService( 2161): disk I/O error (code 3850)
E/DriveAsyncService( 2161): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2161): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2161): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2161): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2161): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2161): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2161): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2161): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2161): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2161): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2161): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2161): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2161): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2161): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2161): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2161): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2161): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2161): Process: com.google.android.gms, PID: 2161
E/AndroidRuntime( 2161): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2161): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2161): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2161): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2161): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2161): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2161): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2161): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2161): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2161): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2161): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2161): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2161): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2161): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2161): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2161): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2161): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2161): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2161): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
D/Process ( 2161): killProcess, pid=2161
D/Process ( 2161): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ActivityManager(  907): Recipient 2161
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms (pid 2161) has died.
D/PMS     (  907): handleWLDeath(423fe9b8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20997ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20992ms
E/SQLiteLog( 1361): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1361): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63feebf0
W/dalvikvm( 1361): threadid=1: thread exiting with uncaught exception (group=0x416fee30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1361): FATAL EXCEPTION: main
E/AndroidRuntime( 1361): Process: com.google.process.gapps, PID: 1361
E/AndroidRuntime( 1361): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1361): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1361): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1361): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1361): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1361): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1361): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1361): 	... 10 more
D/Process ( 1361): killProcess, pid=1361
I/DeviceManagement( 4308): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4308): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
D/Process ( 1361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/DeviceManagement( 4308): WorkflowService: Starting workflow service
I/DeviceManagement( 4308): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d07e98] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4308): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4308): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4308): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4308): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4308): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4640 uid=10099 gids={50099, 3003, 5012}
E/SQLiteLog( 4308): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4308): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5ca96a20
W/DeviceManagement( 4308): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d07e98]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 4308): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 4308): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 4308): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4308): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4308): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4308): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4308): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4308): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4308): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4308): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4308): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4308): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4308): WorkflowService: Stopping workflow service
W/PackageManager(  907): Unable to load service info ResolveInfo{43561720 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  907): Recipient 1361
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.process.gapps (pid 1361) has died.
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20825ms
D/Documents( 4640): Loading roots for com.android.providers.downloads.documents
D/Documents( 4640): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4640): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4640): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4640): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4640): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4640): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4640): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4640): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4640): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4640): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4640): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4640): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4640): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4640): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4640): threadid=1: thread exiting with uncaught exception (group=0x416fee30)
E/AndroidRuntime( 4640): FATAL EXCEPTION: main
E/AndroidRuntime( 4640): Process: com.android.documentsui, PID: 4640
E/AndroidRuntime( 4640): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4640): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4640): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4640): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4640): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4640): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4640): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4640): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4640): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4640): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4640): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4640): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4640): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4640): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4640): 	... 10 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4653 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4664 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  907): killProcessQuiet, pid=4118
I/ActivityManager(  907): Killing 4118:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process (  907): killProcessQuiet, pid=4291
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  907): Killing 4291:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  907): Recipient 4291
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ExternalStorage( 4653): After updating volumes, found 1 active roots
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453369084565.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
D/Process ( 4640): killProcess, pid=4640
D/Process ( 4640): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/dalvikvm( 4664): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4664): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4664): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4664): install
I/MultiDex( 4664): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/MultiDex( 4664): loading existing secondary dex files
I/ActivityManager(  907): Recipient 4118
I/MultiDex( 4664): load found 3 secondary dex files
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bc1c70 +
I/Prism.WidgetManager( 1273): onLoadItems() +
I/MultiDex( 4664): install done
I/ActivityManager(  907): Recipient 4640
I/ActivityManager(  907): Process com.android.documentsui (pid 4640) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=4683 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/GservicesProvider( 4683): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 4683): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 4683): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4683): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4683): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4683): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4683): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 4683): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 4683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4683): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4683): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4683): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4683): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4683): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4683): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4683): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4683): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4683): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4683): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4683): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4683): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4683): threadid=1: thread exiting with uncaught exception (group=0x416fee30)
E/AndroidRuntime( 4683): FATAL EXCEPTION: main
E/AndroidRuntime( 4683): Process: com.google.process.gapps, PID: 4683
E/AndroidRuntime( 4683): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5397)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/AndroidRuntime( 4683): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4683): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4683): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4683): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4683): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4683): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4683): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4683): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4683): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4683): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4683): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4683): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 4683): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 4683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/AndroidRuntime( 4683): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/AndroidRuntime( 4683): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/AndroidRuntime( 4683): 	... 12 more
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
D/Process ( 4683): killProcess, pid=4683
D/Process ( 4683): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ActivityManager(  907): Recipient 4683
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.process.gapps (pid 4683) has died.

```
