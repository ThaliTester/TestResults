#### Test 50650278b86327b_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
E/cutils-trace( 4427): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4427): ====startRecUseTime====
D/htc.customization.log.level( 4427):  is 
W/CustomizationLogLevel( 4427): Level value is invalid, use default level 2
D/CustomizationManager( 4427):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4427): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4427): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4427): Parsing tag category name = system
I/CustomizationCIDLoader( 4427): Parsing tag category name = application
I/CustomizationCIDLoader( 4427): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4427): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4427): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4427): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4427): Parsing tag category name = Settings
D/CustomizationManager( 4427):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4427):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4427): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4427): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4427): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4427): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
D/PMS     (  906): acquireHCC(42358f90): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4427
D/PMS     (  906): acquireHCC(420f7a90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62bd5648 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1111390632
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c775d0
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
D/PMS     (  906): acquireWL(424ecd68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4439 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4439): Copying FileAsset 0x5c8d3430 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1267): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4439): Binding Chromium to main looper Looper (main, tid 1) {41b2d7b8}
I/LibraryLoader( 4439): Expected native library version number "",actual native library version number ""
I/chromium( 4439): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4439): Initializing chromium process, renderers=0
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4380ff80:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4439): 1102331408: getState(). Returning 12
D/PMS     (  906): acquireWL(44236540): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(4271e390): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): releaseWL(44236540): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4439): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4439): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4439): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4439): Local Branch: 
I/Adreno-EGL( 4439): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4439): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4439):                  aa63bbd948f41d15fc72f585e
W/chromium( 4439): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4439): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4439): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4439): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4439): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4439): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4439): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4439): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4439): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4439): CordovaWebView is running on device made by: HTC
,W/AwContents( 4439): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1267
,W/ResourceType( 4439): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4439): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b754c0, mServedView=org.apache.cordova.engine.SystemWebView{41b3b128 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4439): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Enable input method client, pid=4439
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +256ms
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(424ecd68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4439): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4439): JniHelper::setJavaVM(0x41608048), pthread_self() = 1663195776
,D/JX-Cordova( 4439): jxcore cordova android initializing
,W/dalvikvm( 4439): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 11.553MB for 96598-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 11.632MB for 144892-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 11.748MB for 217334-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 11.923MB for 325996-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 12.198MB for 488990-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 13.205MB for 1100216-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 14.077MB for 1650320-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 15.464MB for 2475476-byte allocation
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42135eb8
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42135eb8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c6c90
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42756550
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 17.498MB for 3713210-byte allocation
,W/jxcore-log( 4439): Initializing JXcore engine
,W/jxcore-log( 4439): JXcore engine is ready
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(42358f90): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(420f7a90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
W/jxcore-log( 4439): Starting JXcore engine
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 315ms
D/NfcService( 1249): ScreenObserver: OFF
,D/NfcService( 1249): applyRouting - 0
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): Disable input method client, pid=4439
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42638ab0)
,D/NfcService( 1249): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(4380efa8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/PMS     (  906): releaseWL(4380efa8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  906): onScreenOn
D/PMS     (  906): acquireWL(438396b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(438396b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2379): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1249): applyRouting - 0
,D/MtpService( 2379): [MTP][onReceive]-
,D/NfcService( 1249): applyRouting -2
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): acquireWL(426af618): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
,D/PMS     (  906): releaseWL(426af618): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19780 delay=15s
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:On
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4100): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4100): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4100): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4100): Cust_ConnectToPC   : spcsc>false
D/        ( 4100): Cust_ConnectToPC   : IPT>true
,D/        ( 4100): Cust_ConnectToPC   : Singel_USB>false
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/Settings( 4100): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4100): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4100): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4100): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4100): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
D/NetworkPolicy(  906): updateScreenOn: false
,W/ContextImpl( 4100): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
I/SmartNS_PSService( 4100): onReceive:android.intent.action.USER_PRESENT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
W/Settings( 4100): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4100):  defaultType:0
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/jxcore-log( 4439): Platform android
W/jxcore-log( 4439): 
,W/jxcore-log( 4439): Process ARCH arm
W/jxcore-log( 4439): 
,I/ClockThread( 1114): stop update clock
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4494 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  906): acquireWL(44121a28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(44121a28): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(426dafd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426dafd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1739): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): onScreenOn: 1449756666543
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1739): onScreenOn: 1449756666543
W/ContextImpl( 4494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4494): isEpsOn(), nState = 0
,D/PMS     (  906): acquireWL(438696e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4494 1000 null
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c6c90
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423c6c90, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42756550
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(434f82d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(438696e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19780 mDataStallAlarmIntent=PendingIntent{44236880: PendingIntentRecord{4250ad18 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:Off
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  906): acquireWL(43cc21e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1233): start background delete task...
D/ContactMessageStore( 1233): size: 0 , 0
,D/ContactMessageStore( 1233): Background delete complete
,D/SmartSyncUtils( 4494): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=3852
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Killing 3852:com.google.android.music:main/u0a154 (adj 15): empty #17
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  906): releaseWL(43cc21e0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Recipient 3852
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4494): isEpsOn(), nState = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3852): Died!
,W/ContextImpl( 4494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4494): getMobilePolicyEnabled, result = true
D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
,D/SmartSyncUtils( 4494): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,D/PMS     (  906): acquireWL(43bb45a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): releaseWL(43bb45a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(427bdbd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427bdbd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1739): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1739): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1739): onScreenOff
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42756550
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42756550, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42756550, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42756550
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42756ec0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42756ec0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	,at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,I/jxcore-log( 4439): JXcore Cordova bridge is ready!
I/jxcore-log( 4439): 
,W/jxcore-log( 4439): JXcore engine is started
,I/chromium( 4439): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/ResourceType( 4439): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4439): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b3b128 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/PMS     (  906): releaseWL(434f82d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  906): releaseWL(4271e390): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4439): Toggling radios to true
I/jxcore-log( 4439): 
,D/BluetoothAdapter( 4439): enable(): BT is already enabled..!
,D/WifiManager( 4439): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1359
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
D/WifiService(  906): setWifiEnabled: true pid=4439, uid=10389
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiManager( 4439): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4439): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): TDLS: Tear down peers
I/wpa_supplicant( 1182): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4439): Radios toggled
I/jxcore-log( 4439): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4439): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4439): 
,D/WifiService(  906): New client listening to asynchronous messages
I/jxcore-log( 4439): Perf Test app loaded loaded
I/jxcore-log( 4439): 
I/jxcore-log( 4439): check test folder
I/jxcore-log( 4439): 
I/jxcore-log( 4439): found test : ./testFindPeers.js
I/jxcore-log( 4439): 
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1182): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1182): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1182): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8596bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1182):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1182): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1182): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1182): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  906):    returned true
I/jxcore-log( 4439): found test : ./testSendData.js
I/jxcore-log( 4439): 
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): Wireless event: cmd=0x8b15 len=20
D/WifiNative-wlan0(  906):    returned true,
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2,
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  906):    returned true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(43848498): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): Fast associate: Old scan results
I/wpa_supplicant( 1182): wpa_supplicant_scan enter
I/wpa_supplicant( 1182): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1182): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1182): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1182): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19781 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,D/WifiNative-wlan0(  906): doBoolean: SET pno 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='1'
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WISPrService( 4100): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4100): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiService(  906): New client listening to asynchronous messages
D/WISPrService( 4100): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4100): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1182): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  906):    returned true
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1182): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1182): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1182): nl80211: Survey data missing
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1182): Sorted scan results
I/wpa_supplicant( 1182): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1182): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1182): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1182): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1182): wpa_supplicant_pick_network+
I/wpa_supplicant( 1182): Selecting BSS from priority group 1
I/wpa_supplicant( 1182): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1182): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1182): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1182):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1182):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1182): Start print parameters
I/wpa_supplicant( 1182): wpa_s->wpa_state is 3
I/wpa_supplicant( 1182): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1182): isConcurrentMode() is 0
I/wpa_supplicant( 1182): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1182): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1182): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1182): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1182): wpa_s->reassociate is 1
I/wpa_supplicant( 1182): wpa_s->is_screen_on 0
I/wpa_supplicant( 1182): wpa_s->ifname wlan0
I/wpa_supplicant( 1182): End print parameters
I/wpa_supplicant( 1182): selected network = 1
D/wpa_supplicant( 1182): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85984e8  current_ssid=0x0
D/wpa_supplicant( 1182): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1182): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1182): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1182): check if in concurrent case
I/wpa_supplicant( 1182): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1182): RSN: PMKSA cache search - network_ctx=0xb85984e8 try_opportunistic=0
D/wpa_supplicant( 1182): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1182): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1182): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1182): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1182): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1182): nl80211: Unsubscribe mgmt frames handle 0xb,8597718 (mode change)
D/wpa_supplicant( 1182): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8597718
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb8597718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1182):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1182):   * freq=2412
D/wpa_supplicant( 1182):   * Auth Type 0
D/wpa_supplicant( 1182):   * WPA Versions 0x2
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1182): nl80211: Connect request send successfully
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1182): reply (376) for get BSS: id=0
I/wpa_supplicant( 1182): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1182): freq=5220
I/wpa_supplicant( 1182): level=-51
I/wpa_supplicant( 1182): tsf=0000000021860309
I/wpa_supplicant( 1182): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1182): ssid=NG7005g
I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=1
I/wpa_supplicant( 1182): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): freq=2412
I/wpa_supplicant( 1182): level=-50
I/wpa_supplicant( 1182): tsf=0000000105803542
I/wpa_supplicant( 1182): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1182): ssid=NG700
I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=2
I/wpa_supplicant( 1182): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1182): freq=2427
I/wpa_supplicant( 1182): level=-76
I/wpa_supplicant( 1182): tsf=0000000021860317
I/wpa_supplicant( 1182): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1182): ssid=Gonzos
I/wpa_supplicant( 1182): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
V/NativeCrypto( 1360): Read error: ssl=0x6632f848: I/O error during system call, Connection timed out
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiManager( 1218): getScanResults enter 
V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x6632f848: I/O error during system call, Broken pipe
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 21860309, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 105803542, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 21860317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/PMS     (  906): acquireWL(439a8140): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  906): == begin of scan result ==
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): == (3) end of scan result ==
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  362): [NET] entry_id:7   entry:0xb78f6110  removed 
D/libc    (  362): [NET] entry_id:3   entry:0xb78fa320  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb78f9fd8  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb78fa428  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb78fa240  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb78fa0e8  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb78f5f60  removed 
D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(43d04de8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  362): RTNETLINK answers: No such process
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/WifiNative-wlan0(  906): doBoolean: SET pno 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 76
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/wpa_supplicant( 1182): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/PMS     (  906): releaseWL(439a8140): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/BatSI   (  906): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): wpa_supplicant_scan enter
I/wpa_supplicant( 1182): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1182): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906):    returned true
E/wpa_supplicant( 1182): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1182): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1182): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1182): Failed to initiate AP scan
,I/wpa_supplicant( 1182): Failed to initiate AP scan, Failed_to_scan_counter:1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
D/PMS     (  906): releaseWL(43d04de8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/chromium( 4439): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1182): nl80211: Connect event
D/wpa_supplicant( 1182): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1182): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1182): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1182): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1182): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1182): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1182): TDLS: Remove peers on association
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1182): EAPOL: enable timer tick
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1182): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1182): Get randomness: len=32 entropy=2
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1182): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85979f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1182):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 10
D/WifiStateMachine(  906): This record is existed, only update it...
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1182): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f7eb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1182):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1182): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1182): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1182): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,E/wpa_supplicant( 1182): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1182): set send_ind_to_ndc = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1182): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 1182): EAPOL authentication completed successfully
I/wpa_supplicant( 1182): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4100): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4100): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  906): doBoolean: SET pno 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 1
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1182): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(43e61d18): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d10b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d10b8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ProcessCpuTracker(  906): Skipping unknown process pid 4547
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  906): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): releaseWL(43e61d18): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=66 [3][2][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  906): WAN detection
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@424b1050
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4100): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(44078df0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4565 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): acquireWL(436aca60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/PMS     (  906): releaseWL(436aca60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4286/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10076)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(44003a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4286/10100)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(44003a00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(44078df0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
,I/MusicStore( 4565): Database version: 95
,W/ContextImpl( 4565): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/wpa_supplicant( 1182): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1182): EAPOL: disable timer tick
,W/ContextImpl( 4565): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4565): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4565): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4565): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4565, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 4565): Registered
,I/MediaRouter( 4565): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (4565/10154)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2379/10021)
,I/NetworkMonitor( 4565): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4588 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4565): getSelectedRoute
,I/NetworkMonitor( 4565): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4565/10154)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4565, uid=10154, userID:0
,D/PMS     (  906): acquireWL(43868db8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/Process (  906): killProcessQuiet, pid=4220
,D/ACRA    ( 4588): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 4220:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMS     (  906): releaseWL(43868db8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ACRA    ( 4588): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4588): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  906): Recipient 4220
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/SystemClassLoaderAdder( 4588): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 4588): Preparing secondary program dexes.
V/DexLibLoader( 4588): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4588): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4588): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4588): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4588): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4588): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4588): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4588): Dex already copied
D/OdexVerifier( 4588): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4588): Creating class loader
,V/DexLibLoader( 4588): Finished creating class loader,
,V/DexLibLoader( 4588): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4588): Dex already copied
D/OdexVerifier( 4588): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4588): Creating class loader
,V/DexLibLoader( 4588): Finished creating class loader
V/DexLibLoader( 4588): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4588): Dex already copied
D/OdexVerifier( 4588): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4588): Creating class loader
,V/DexLibLoader( 4588): Finished creating class loader
V/DexLibLoader( 4588): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4588): Dex already copied
D/OdexVerifier( 4588): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4588): Creating class loader
,V/DexLibLoader( 4588): Finished creating class loader
V/DexLibLoader( 4588): Verifying classes from secondary dexes.
,D/DexLibLoader( 4588): DexLibLoader.ensureDexLoaded took 20 ms
,D/PMS     (  906): releaseWL(43848498): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/PMS     (  906): acquireWL(42721080): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10076)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4565/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4286/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3887/10053)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/NetworkMonitor( 4565): type=WIFI subType= reason=null isConnected=true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
D/PMS     (  906): acquireWL(4398ced0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4286/10100)
D/PMS     (  906): releaseWL(4398ced0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): releaseWL(42721080): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4588): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4588): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4588): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4588): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4588): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4588): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4588): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4588): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4588): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4588): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4588): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4588): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4588): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4588): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3828
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3828:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4610 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1320): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,W/fb4a(:<default>):UserScope( 4588): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4588): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4610): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4610): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4610): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4610): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4588): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  906): killProcessQuiet, pid=4035
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4624 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 4035:com.google.android.talk/u0a111 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4610/10079)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4610/10079)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4610/10079)
,D/PMS     (  906): acquireWL(43607018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Recipient 3828
,I/ActivityManager(  906): Recipient 4035
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(426fc550): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2170): Checkin interval check for package: unspecified last checkin: 1449756616563 min interval config: 0 actual interval: 54814
D/PMS     (  906): releaseWL(43607018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4639 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4255
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CheckinService( 2170): Checking schedule, now: 1449756671402 next: 1449756646540
,I/CheckinService( 2170): active receiver: enabled
I/ActivityManager(  906): Killing 4255:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2170, uid=10029, userID:0
E/dalvikvm( 4588): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4588): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4588): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4588): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4588): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4588): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4588): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4588): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4588): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4588): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4588): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4588): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4588): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4588): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4588): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4588): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4588): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4588): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4255
,I/CheckinService( 2170): Preparing to send checkin request
,I/EventLogService( 2170): Accumulating logs since 1449756612205
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
,I/dalvikvm-heap( 4588): Grow heap (frag case) to 9.921MB for 39954-byte allocation
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/CheckinRequestBuilder( 2170): Checkin reason type: 8 attempt count: 1
,W/ContextImpl( 4639): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4639): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2170): Failed to find provider info for com.google.android.wearable.settings
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4639): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4588): Grow heap (frag case) to 9.999MB for 79892-byte allocation
W/ContextImpl( 4639): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4639): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4588): Grow heap (frag case) to 10.061MB for 84664-byte allocation
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2170/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4639/10151)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,V/WebViewChromiumFactoryProvider( 4639): Binding Chromium to main looper Looper (main, tid 1) {41b342d8}
,I/LibraryLoader( 4639): Expected native library version number "",actual native library version number ""
,I/chromium( 4639): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4639): Initializing chromium process, renderers=0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AudioManagerAndroid( 4639): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(426d4bd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(425c0f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  906): releaseWL(425c0f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4639): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4639): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4639): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4639): Local Branch: 
I/Adreno-EGL( 4639): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4639): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4639):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4639): Starting up...
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4639/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4639/10151)
,I/dalvikvm-heap( 4588): Grow heap (frag case) to 10.273MB for 75760-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4676 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{438db9b8 u0 ReceiverList{438798e0 4588 com.facebook.katana/10027/u0 remote:437d3880}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{438db9b8 u0 ReceiverList{438798e0 4588 com.facebook.katana/10027/u0 remote:437d3880}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437a5e68 u0 ReceiverList{437a5e08 4588 com.facebook.katana/10027/u0 remote:4413c6e0}}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/Process (  906): killProcessQuiet, pid=4286
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4286:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4676): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
,W/dalvikvm( 4676): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
I/MultiDex( 4676): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4676): install
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/MultiDex( 4676): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4676): loading existing secondary dex files
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,I/MultiDex( 4676): load found 3 secondary dex files
,I/MultiDex( 4676): install done
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2379/10021)
,W/dalvikvm( 4676): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4676): VFY: unable to resolve instance field 36
,W/dalvikvm( 4676): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PMS     (  906): acquireWL(4385f5b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4385f5b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4610): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4610): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  906): Recipient 4286
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1320): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4639/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2170, uid=10029, userID:0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4588): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/dalvikvm-heap( 4076): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4588): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4588): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 4676): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1218): callingUid 10029, callindPid: 1218
,W/dalvikvm( 4676): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4676): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/MDM     ( 1218): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2170): Restart initialization of location
,W/dalvikvm( 4676): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4676): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4676): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4676): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4676): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1218): No location to return for getLastLocation()
,W/FusedLocationProvider( 1218): location=null
D/PMS     (  906): acquireWL(43b87ed0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43b87ed0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4676): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2394175193
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4309
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4309:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4309
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =d228 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/WVCdm   (  370): PrepareKeyRequest: nonce=312529804
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,I/WVCdm   (  370): CdmEngine::CloseSession
,W/Settings( 4676): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4676): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4676): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4676): Local Branch: 
I/Adreno-EGL( 4676): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4676): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4676):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4676): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4676): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4676): Local Branch: 
I/Adreno-EGL( 4676): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4676): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4676):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4676/10029)
,I/Adreno-EGL( 4676): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4676): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4676): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4676): Local Branch: 
I/Adreno-EGL( 4676): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4676): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4676):                  aa63bbd948f41d15fc72f585e
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/CheckinRequestBuilder( 2170): Classify the device as Phone.
,D/libc    ( 2170): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2170): [NET] getaddrinfo-,err=8
D/libc    ( 2170): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2170): [NET] getaddrinfo-, 1
D/libc    ( 2170): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =eab3 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 79
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2170): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2170): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2170): [NET] getaddrinfo-,err=8
,D/libc    ( 2170): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2170): [NET] getaddrinfo-,err=8
,D/libc    ( 2170): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2170): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2170): Sending checkin request (12078 bytes)
,I/jxcore-log( 4439): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4439): 
,I/CheckinRequestBuilder( 2170): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2170): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2170/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=8 [24][2][0]
,I/CheckinRequestBuilder( 2170): Classify the device as Phone.
,I/CheckinTask( 2170): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2170): Checking schedule, now: 1449756673999 next: 1450279610991
,I/CheckinService( 2170): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2170, uid=10029, userID:0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,D/CheckinService( 2170): Recording last checkin time for package unspecified as 1449756674017
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(426fc550): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2170/10029)
,D/PMS     (  906): acquireWL(441804e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
,D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =e4e8 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 224
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/PMS     (  906): acquireWL(4411c568): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/PMS     (  906): releaseWL(441804e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/PMS     (  906): releaseWL(4411c568): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43c45a98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(43c45a98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426d4bd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  906): acquireWL(431d6e60): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4565 10154 null
,W/ContextImpl( 4565): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4565, uid=10154, userID:0
,I/MusicLeanback( 4565): Conditions not met for autocaching.
,I/MusicLeanback( 4565): Stop autocaching.
D/PMS     (  906): releaseWL(431d6e60): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4565): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [10][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,W/fb4a(:<default>):UserScope( 4588): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4588): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4588): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4588/10027)
,I/GAV2    ( 4639): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=3887
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3887:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3887
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4328
,I/ActivityManager(  906): Killing 4328:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4328
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1337): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4733 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1267): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  906):   Scheme: "smsto"
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
W/AccTypeManager( 1337): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1337): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsUpdated
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,E/ExternalAccountType( 1337): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
,D/PhoneApp( 1233): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4733): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4733): MmsConfig.loadMmsSettings
,W/dalvikvm( 4733): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4733): VFY: unable to resolve instance field 36
,W/dalvikvm( 4733): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4733): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  906): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4756 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,D/MessageFrequencyProvider( 4756): onCreate
,D/MmsCustomizationProvider( 4756): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4756): GetPrviateResource
,V/GetPrviateResource( 4756): GetPrviateResource
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4733, uid=10111, userID:0
,D/MmsCustomizationProvider( 4756): query uri: content://htc-mms-customization/mms-ua/ua_profile
W/PackageManager(  906): Unable to load service info ResolveInfo{43cc3c68 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,W/Settings( 4733): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel   ( 4733): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4733): MmsConfig.loadFromDatabase
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4733, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4733, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4733, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4733, uid=10111, userID:0
E/Babel   ( 4733): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4733): MmsConfig.loadFromResources
E/Babel   ( 4733): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4733): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4733, uid=10111, userID:0
D/PMS     (  906): acquireWL(42560150): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4733 10111 null
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2840): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ProviderInstaller( 4733): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4756): sense_version=6.0
,D/BTAccessoryUtil( 4756): createReceiver
,D/BTAccessoryUtil( 4756): registerReceiver return intent = null
D/MessageCustFlag( 4756): sku_id=99
,W/SystemReader( 4756): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  906): acquireWL(440a3478): PARTIAL_WAKE_LOCK  AsyncService 0x1 4076 10160 null
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  906): acquireWL(43296530): PARTIAL_WAKE_LOCK  Icing 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4756): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4756): networkCode: 
,D/MessageCustFlag( 4756): sku_id=99
D/MmsConfig( 4756): SIE smsPri: null
,D/MmsConfig( 4756): networkCode: 
,I/dalvikvm-heap( 4076): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(43296530): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42560150): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/HtcTelephonyCapability( 4756): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4756): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4756): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4756): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(440a3478): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  906): acquireWL(434d6630): PARTIAL_WAKE_LOCK  Icing 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4076): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
,D/Process (  906): killProcessQuiet, pid=4273
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4273:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/PackageBroadcastService( 2170): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2170): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  906): Resuming delayed broadcast
,I/Icing   ( 2170): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  906): Recipient 4273
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1218): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(43340bc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43340bc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(433049b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(434e6280): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(433049b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(434e6280): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2840): UpdateCorporaTask done [took 558 ms] updated apps [took 558 ms] 
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@41bc3d50 +
,I/Prism.WidgetManager( 1267): onLoadItems() +
,I/Icing   ( 2170): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2170): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(434d6630): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1267): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1267): onLoadItems() -
,I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@41bc3d50 -
,D/PhoneApp( 1233): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1233): -- N1 =0
,D/PhoneApp( 1233): -- N2 =0
,D/PhoneApp( 1233): -- N3 =0
,D/Messaging( 4756): mNeedToUpdateDate2 start
,D/MmsConfig( 4756): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4756): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4756): 
D/MmsAsyncWorkHandler( 4756): HM tk = 20001
D/ReportIndicatorCache( 4756): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4756): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b403c0
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,I/Messaging( 4756): mccmnc> 
D/MmsSmsV2Provider( 1233):  phoneType = -1
,D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4756): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4756): [DraftCache/1] refresh
,D/MmsConfig( 4756): networkCode: 
,D/Messaging( 4756): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1233):  phoneType = -1
,D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4756): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4756): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4756): createReceiver
,D/MessageCustFlag( 4756): sense_version=6.0
,D/Jerry   ( 4756): start to preload cursor >>>>>>>
,D/Messaging( 4756): mNeedToUpdateDate2: false
D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/MmsSmsV2Provider( 1233):  phoneType = -1
D/TelephUtils( 1233): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1233): Update uri=content://mms, match=0
,V/MmsProvider( 1233): selection=st=129 AND m_type!=134
,D/Messaging( 4756): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4756): TransactionService is going to be woken up.
,V/TransactionService( 4756): 1-Creating TransactionService
D/Messaging( 4756): ViewCache CreatePreload
,D/Messaging( 4756): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4756): onStartCommand: 1
,D/Cust_MMSMS( 4756): _has_set_default_values_2=true
,D/MmsSystemEventReceiver( 4756): unRegisterForConnectionStateChanges
V/TransactionService( 4756): 4-Handling incoming message: { when=-2ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4756): Loading previous transactions.
,D/MsgPreferenceUtils( 4756): def_index: 0
D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1233): device_type: 1
,D/MsgPreferenceUtils( 4756): globalIndex = 1
,D/MsgPreferenceUtils( 4756): phone state: true
D/MsgPreferenceUtils( 4756): sd state: false
D/MsgPreferenceUtils( 4756): vIndex = 0
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1233):  phoneType = -1
,D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/TransactionService( 4756): Force set service start id to 1
V/TransactionService( 4756): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4756): unRegisterForConnectionStateChanges
,D/TransactionService( 4756): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4756): Destroying TransactionService
,V/TransactionService( 4756): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1233): sku_id=99
,D/DraftCache( 4756): [DraftCache/472] rebuildCache
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1233):  phoneType = -1
,D/MmsSmsV2Provider( 1233): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4756): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/Jerry   ( 1233): URI_DRAFT
,D/DraftCache( 4756): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4756): [DraftCache/472] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4756): 
D/MmsAsyncWorkHandler( 4756): HM tk = 20002
D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1233): sku_id=99
,D/TelephUtils( 1233): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1233): sku_id=99
,D/PMS     (  906): acquireWL(440630d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{43cf3ed0: PendingIntentRecord{4266bae0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122998, Int=0
,D/PMS     (  906): releaseWL(440630d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(441dde38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43b54d70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(441dde38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43b54d70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4404c588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(4404c588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43306d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): acquireWL(426d5238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(440ea100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1218): Vacuum at: now=1449756685847 tag=VacuumService
D/PMS     (  906): releaseWL(43306d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426d5238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43ded668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(43ded668): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43bfe910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/PMS     (  906): releaseWL(440ea100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43bfe910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43474e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(43474e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43cdf7a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43cdf7a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43843cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43341de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43341de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43be7078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43843cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43cd11a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(43cd11a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1218): Scheduling Phenotype for one-off execution 4850 seconds from now (1449756686602)
,D/GetConfigurationSnapshotOperation( 1218): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1218): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1218): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1218): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/GAV4    ( 4733): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
W/dalvikvm( 1218): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8
D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1218): [NET] getaddrinfo-, 1
,D/libc    ( 1218): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =c323 +++++
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 215
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1218): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8
D/libc    ( 1218): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1218): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [8][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(43be7078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42595e78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(42595e78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42492548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(42492548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(420844d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(420844d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4259bfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4259bfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42475200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42696480: PendingIntentRecord{41e74438 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134053, Int=0
,D/PMS     (  906): releaseWL(42475200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1511): service - onCreate()
,D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1511): service - mHandler: update timezone
,D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1511): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1511): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41c551e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 3 7 2 11
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1511): service - mHandler: update timezone
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1511): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1511): service - showManualTimeZoneSelector() send notification (single)
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f609a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 2 7 2 11
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(4330dec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42228a90: PendingIntentRecord{424fb358 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141152, Int=0
D/PMS     (  906): acquireWL(43177dc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(4330dec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =4285 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=243
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(43177dc8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  906): killProcessQuiet, pid=4359
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4359:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4359
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1233): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43cb1720 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(425eb948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425eb948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4374
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4374:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4374
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(433bd4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{42932818: PendingIntentRecord{42be93d0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=170419, Int=0
,D/PMS     (  906): releaseWL(433bd4a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1233): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(4245de90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4245de90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(433bacb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(433bacb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1360): disconnect managed GoogleApiClient
,D/PMS     (  906): acquireWL(4251ad50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217371, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4251ad50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(430e3868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430e3868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43828240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=277372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43828240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4439): Connected to the server!
I/jxcore-log( 4439): 
,I/chromium( 4439): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  906): acquireWL(42560140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42560140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(437d1208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=337372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437d1208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(426a2ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426a2ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425bc550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425bc550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43ba57d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ba57d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42c4da80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c4da80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425c4ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=457372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425c4ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(440ca970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440ca970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426961f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517372, Int=0
,D/PMS     (  906): releaseWL(426961f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43d0a410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d0a410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42ab3cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=577372, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ab3cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425d9028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425d9028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1233): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1233): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1233): sku_id=99
,D/ContactMessageStore( 1233): start background delete task...
,D/ContactMessageStore( 1233): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1233): size: 0 , 0
,D/ContactMessageStore( 1233): Background delete complete
,D/PMS     (  906): acquireWL(425f0480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1267): Grow heap (frag case) to 12.642MB for 50416-byte allocation
D/PMS     (  906): releaseWL(425f0480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4005
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4005:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4005
,D/PMS     (  906): acquireWL(437e43e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437e43e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4255ff38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4255ff38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43d0ccc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d0ccc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(437649d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=757372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437649d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431630d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431630d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42460508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=817372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42460508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43da7400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43da7400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4270a548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=877372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1267): Grow heap (frag case) to 12.642MB for 50416-byte allocation
,D/PMS     (  906): releaseWL(4270a548): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42c2c270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c2c270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42604be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=937372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42604be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(439b9220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(439b9220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(427c2b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427c2b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438132a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e25338: PendingIntentRecord{424bb808 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783182, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4852 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{423d09a0: PendingIntentRecord{4253b890 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449756774178, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{42c2be28: PendingIntentRecord{426a1f58 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449756914057, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{41d82a28: PendingIntentRecord{42654be0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449757494631, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{441b7548: PendingIntentRecord{42638268 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449757566645, Int=0
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(427c56d8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,W/ContextImpl( 4494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(437da870): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4494): call getInstance()
,D/SmartSyncUtils( 4494): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4494): MY_DEBUG = false
D/PMS     (  906): releaseWL(427c56d8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(438132a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(439329d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4494 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4494): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4494): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4494): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4494): SettingOnTime = 1449813600000, randomSettingOnTime = 1449811659000
D/SmartSyncScreenOnOffTimeReceiver( 4494): SettingOffTime = 1449799200000, randomSettingOffTime = 1449804877000
D/SmartSyncScreenOnOffTimeReceiver( 4494): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4494): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4494): bNightModeTurnOffOnce = false
D/PMS     (  906): releaseWL(439329d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/EventLogService( 2170): Aggregate from 1449756671439 (log), 1449755114012 (data)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4852/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(437da870): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4409
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4409:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4409
,D/PMS     (  906): acquireWL(440a30c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{4269b9d0: PendingIntentRecord{42438280 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1011721, Int=0
,D/PMS     (  906): acquireWL(43ba76d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43ba76d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(440a30c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43f258f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
,D/PMS     (  906): releaseWL(43f258f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=7 [227][18][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43d04a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d04a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(437853d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437853d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43b87948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1267): Grow heap (frag case) to 12.642MB for 50416-byte allocation
,D/PMS     (  906): releaseWL(43b87948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  906): Start proc com.htc.cs.dm for service com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService: pid=4870 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  906): acquireWL(43994c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10098}
V/AlarmManager(  906): sending alarm PendingIntent{4261ad38: PendingIntentRecord{425e9640 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1449757644072, Int=0
,D/PMS     (  906): releaseWL(43994c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10098}
,I/DeviceManagement( 4870): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4870 dbg=false s=true
,I/DeviceManagement( 4870): WorkflowService: Starting workflow service
,I/DeviceManagement( 4870): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41b59bd0] args=[Bundle[mParcelledData.dataSize=60]]
I/DeviceManagement( 4870): UpdateWorkflow: ==================================================
I/DeviceManagement( 4870): UpdateWorkflow: TTL update...
,I/DeviceManagement( 4870): UpdateWorkflow: ==================================================
,I/DeviceManagement( 4870): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4870): SessionStateController: Checking invariants...
,I/DeviceManagement( 4870): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 4870): SessionStateController: Checking invariants...
,I/DeviceManagement( 4870): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 4870): Perf: *** Cache update - start...
I/DeviceManagement( 4870): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 4870): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 4870): Perf: *** Enabled app cache update - complete: 2 ms
I/DeviceManagement( 4870): Perf: *** Config cache update - start...
I/DeviceManagement( 4870): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 4870): ConfigCacheController: *** Updating stale config cache entries...
,W/dalvikvm( 4870): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 4870): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 4870): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,W/System.err( 4870): Starting the internal HTTP client
,I/DeviceManagement( 4870): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEwLTE0VDEwOjI4OjM4LjU4Mlo
,I/DeviceManagement( 4870): DeviceClientResource: Active network...
I/DeviceManagement( 4870):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/BuildInfo( 4870): Created new instance: com.htc.cs.lib.hms.BuildInfo@41db9eb8
,I/DeviceManagement( 4870): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [10][0][0]
,D/libc    ( 4870): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4870): [NET] getaddrinfo-, 1
,D/libc    ( 4870): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  362): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4870): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4870): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4870): [NET] getaddrinfo-,err=8
D/libc    ( 4870): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4870): [NET] getaddrinfo-, 1
,D/libc    ( 4870): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =cc2f +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=204
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4870): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4870): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4870): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4870): DeviceClientResourceController: handleDirectives: []
W/dalvikvm( 4870): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 4870): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 4870): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4870): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 4870): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 4870): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4870): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4870): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 4870): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4870): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 4870): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4870): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 4870): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 4870): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 4870): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
,W/dalvikvm( 4870): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 4870): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 4870): isCompatible false
I/System.out( 4870): createObjectMapper
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
,I/System.out( 4870): isCompatible false
,I/DeviceManagement( 4870): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 4870): DeviceClientResource: Active network...
I/DeviceManagement( 4870):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=33 [12][4][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
,D/libc    ( 4870): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4870): [NET] getaddrinfo-, 1
,D/libc    ( 4870): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  362): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4870): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4870): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4870): [NET] getaddrinfo-,err=8
D/libc    ( 4870): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4870): [NET] getaddrinfo-, 1
D/libc    ( 4870): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =ce08 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4870): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4870): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 4870): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4870): DeviceClientResourceController: handleDirectives: []
I/System.out( 4870): isCompatible false
I/System.out( 4870): createObjectMapper
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
,I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
,I/System.out( 4870): isCompatible false
,I/DeviceManagement( 4870): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 4870): DeviceClientResource: Active network...
I/DeviceManagement( 4870):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=10 [10][1][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (4870/10098)
,D/libc    ( 4870): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 4870): [NET] getaddrinfo-, 1
,D/libc    ( 4870): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  362): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4870): [NET] getaddrinfo_proxy-, success
D/libc    ( 4870): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 4870): [NET] getaddrinfo-,err=8
D/libc    ( 4870): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 4870): [NET] getaddrinfo-, 1
D/libc    ( 4870): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =79b1 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4870): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 4870): DMServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4870): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 4870): DeviceClientResourceController: handleDirectives: []
I/System.out( 4870): isCompatible false
,I/System.out( 4870): createObjectMapper
,I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
I/System.out( 4870): isCompatible false
,I/System.out( 4870): isCompatible false
,I/DeviceManagement( 4870): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 4870): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 4870): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 4870): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 4870): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 4870): AlarmController: Scheduling TTL alarm for: 2015.12.11 at 15:27:26.847 CET (due to: com.htc.launcher)
,I/DeviceManagement( 4870): Perf: *** Config cache update - complete: 2418 ms
,I/DeviceManagement( 4870): Perf: *** Cache update - complete: 2421 ms
,I/DeviceManagement( 4870): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41b59bd0]
,I/DeviceManagement( 4870): WorkflowService: Stopping workflow service
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=4870, uid=10098, userID:0
,D/Process (  906): killProcessQuiet, pid=4610
,I/ActivityManager(  906): Killing 4610:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4610
,D/PMS     (  906): acquireWL(43ba6030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ba6030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(439407c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(439407c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(438b42c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1117372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438b42c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438b3fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438b3fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4389acc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4389acc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43862598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1177372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43862598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438622d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438622d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43856d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43856d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(432e64a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(432e64a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426072e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(426072e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42567c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1297372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42567c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42399170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(42399170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4100): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4100): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4100): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4100): Cust_ConnectToPC   : spcsc>false
D/        ( 4100): Cust_ConnectToPC   : IPT>true
,D/        ( 4100): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4100): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4100): Index of the first 1 = 3
W/ContextImpl( 4100): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4100): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4100): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4100): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4100): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/SmartNS_Utility( 4100): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4100): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(4260c1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4260c1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43785950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1357372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43785950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424bf120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(424bf120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4244ddd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4244ddd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43cc2388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1417372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43cc2388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4269b528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4269b528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424466f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424466f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(437eff18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1477372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437eff18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4270aee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4270aee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4268ab58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(4268ab58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42d798c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1537372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42d798c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426d1ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426d1ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42638680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42638680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42409eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1597372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42409eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b7abd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43b7abd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(423f8610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(423f8610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(431fdf50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1657372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1267): Grow heap (frag case) to 12.642MB for 50416-byte allocation
,D/PMS     (  906): releaseWL(431fdf50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424d09d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(424d09d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(430567b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430567b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42722200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1717372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42722200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4406e588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4406e588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42618268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42618268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43ded2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1777371, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ded2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a014b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a014b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43857650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43857650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43bc6d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41e25338: PendingIntentRecord{424bb808 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1724084, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41d81390: PendingIntentRecord{42521a48 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1813374, Int=0
,D/PMS     (  906): acquireWL(43778c08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(43bc6d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43869f28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=6 [143][9][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42d81478): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(437733f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): releaseWL(43778c08): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(43869f28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4376e6e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4376e6e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(425e9228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(425e9228): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43671418): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43671418): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1218/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4245a498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42d81478): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  906): releaseWL(4245a498): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315361813541
,W/AlarmManager(  906): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{441d69a0: PendingIntentRecord{442518c8 com.google.android.gms startService}}) : type=2 triggerAtTime=315361813541 win=-1 tElapsed=315361813541 maxElapsed=551881813540 interval=0 standalone=false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43d0a790): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(437733f0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  906): releaseWL(43d0a790): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(4371ef98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1837372, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  906): Prepared write state in 34ms
,I/ProcessStatsService(  906): Prepared write state in 26ms
,I/ProcessStatsService(  906): Prepared write state in 13ms
,D/PMS     (  906): releaseWL(4371ef98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-09-18-52-17.bin
,D/PMS     (  906): acquireWL(425c1d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d81390: PendingIntentRecord{42521a48 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1843444, Int=0
,D/PMS     (  906): acquireWL(42646d80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(425c1d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43975408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42646d80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43975408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(425c99a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(425c99a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4337f720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4337f720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43bffe08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424285d8: PendingIntentRecord{41f4fd48 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1897371, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bffe08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435085b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f8b650: PendingIntentRecord{425fde08 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820711, Int=1800000
V/AlarmManager(  906): sending alarm PendingIntent{423c3e68: PendingIntentRecord{427c4a20 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1844843, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4389be08: PendingIntentRecord{42438280 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1911794, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{41d82a28: PendingIntentRecord{42654be0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449758394631, Int=900000
,D/PMS     (  906): acquireWL(43bca240): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  906): releaseWL(43bca240): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/Process (  906): killProcessQuiet, pid=4639
I/ActivityManager(  906): Killing 4639:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Process (  906): killProcessQuiet, pid=4624
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4624:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  906): Recipient 4624
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
D/PMS     (  906): acquireWL(43a07798): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43a07798): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 4639
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(4416f3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=12 [16][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
W/ContextImpl( 4494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(435085b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/BatSI   (  906): Couldn't get kernel wake lock stats
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315361813541
D/PMS     (  906): acquireWL(441422f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315361813541
D/PMS     (  906): releaseWL(441422f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(437e2548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/ChimeraCfgMgr( 2170): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2170): Module APK com.google.android.play.games already loaded
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  906): releaseWL(4416f3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 2170): VFY: unable to resolve virtual method 499: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/dalvikvm( 1360): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1360): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1360): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
W/BatSI   (  906): Couldn't get kernel wake lock stats
W/dalvikvm( 1360): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
V/AccountUtils( 2170): 0 accounts found with uca feature
I/GamesSyncAdapter( 2170): Starting sync for 3a3529a
D/libc    ( 1360): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =95e9 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
W/GamesSyncAdapter( 2170): User is not G+ enabled. Aborting sync
I/GamesSyncAdapter( 2170): Sync duration for 3a3529a: 23
D/libc    ( 1360): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/PMS     (  906): releaseWL(437e2548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43cdf2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/ChimeraCfgMgr( 2170): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2170): Module APK com.google.android.play.games already loaded
W/dalvikvm( 2170): VFY: unable to resolve virtual method 349: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315361813541
D/PMS     (  906): releaseWL(43cdf2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(434bd348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
D/PMS     (  906): acquireWL(4223f128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023014
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023818
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023823
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023827
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025132
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025144
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028093
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315361813541
D/Process (  906): killProcessQuiet, pid=4565
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/PMS     (  906): releaseWL(4223f128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/ActivityManager(  906): Killing 4565:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
D/ChimeraCfgMgr( 2170): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2170): Module APK com.google.android.play.games already loaded
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/ActivityManager(  906): Recipient 4565
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 4565): Died!
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): releaseWL(434bd348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/cutils-trace( 4928): Error opening trace file: No such file or directory (2)
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
E/dalvikvm( 2170): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method com.google.android.gms.games.ui.util.UiUtils.constructButtonBackground
W/dalvikvm( 2170): VFY: unable to resolve new-instance 177 (Landroid/graphics/drawable/RippleDrawable;) in Lcom/google/android/gms/games/ui/util/UiUtils;
D/CustomizationManager( 4928): ====startRecUseTime====
D/htc.customization.log.level( 4928):  is 
W/CustomizationLogLevel( 4928): Level value is invalid, use default level 2
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/CustomizationManager( 4928):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4928): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4928): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4928): Parsing tag category name = system
I/CustomizationCIDLoader( 4928): Parsing tag category name = application
I/CustomizationCIDLoader( 4928): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4928): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4928): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4928): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4928): Parsing tag category name = Settings
D/CustomizationManager( 4928):  Read CID file spent 0.148 (s)
D/CustomizationManager( 4928):  All configurations done spent 0.148 (s)
W/HtcNativeFlag( 4928): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4928): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4928): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4928): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4928, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4439
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 4439:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906):   Force finishing activity ActivityRecord{420dff18 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  906): Copying FileAsset 0x6ffa29a8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/InputDispatcher(  906): channel '4261f480 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '4261f480 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '4261f480 com.test.thalitest.MainActivity (s)'
I/WindowManager(  906): WINDOW DIED Window{4261f480 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
W/PackageSettings(  906): Skipping PackageSetting{422f0b50 com.example.hello/10396} due to missing metadata
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4439 uid 10389
W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(425c8960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1218 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1337): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsRemoved
D/PMS     (  906): releaseWL(425c8960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  906):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1337): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1337): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/IcingCorporaProvider( 2840): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4956 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
E/ExternalAccountType( 1337): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1233 :
D/PhoneApp( 1233): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PMS     (  906): acquireWL(4259de80): PARTIAL_WAKE_LOCK  Icing 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4259de80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(424c8d20): PARTIAL_WAKE_LOCK  Icing 0x1 2170 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 2840): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2840): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63c97af0
E/IcingCorporaProvider( 2840): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2840): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2840): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2840): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2840): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2840): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2840): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2840): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2840): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2840): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2840): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2840): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2840): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2840): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2840): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2840): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2840): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2840): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2840): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2840): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2840): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2840): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2840): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2840): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2840): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2840): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2840): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2840): 	... 15 more
W/IcingCorporaProvider( 2840): notifyTableChanged failed.
W/IcingCorporaProvider( 2840): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2840): UpdateCorporaTask done [took 251 ms] updated apps [took 251 ms] 
D/PMS     (  906): releaseWL(424c8d20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  906): Unable to load service info ResolveInfo{42721478 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4956): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4956): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4956): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4956): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4956): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4956): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4956): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4956): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4956): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4956): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4956): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4956): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4956): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4956): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4956): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4956): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4956): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4956): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4956): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4956): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4956): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4956): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4956): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4956): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4956): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4956): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4956): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4956): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4956): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4956): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4956): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4956): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4956): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4956): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4956): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4956): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4956): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4956): threadid=11: thread exiting with uncaught exception (group=0x41700e30)
E/AndroidRuntime( 4956): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4956): Process: com.google.android.apps.docs, PID: 4956
E/AndroidRuntime( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4956): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4956): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4956): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4956): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4956): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4956): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4956): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4956): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4956): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4956): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4956): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4956): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4956): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4956): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4956): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4956): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4956): Opened ClientFlag.db in read-only mode
D/Process ( 4956): killProcess, pid=4956
D/Process ( 4956): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4975 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4956
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4956) has died.
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4975): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4975): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4975): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4975): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4975): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4975): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4975): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4975): threadid=10: thread exiting with uncaught exception (group=0x41700e30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4975): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4975): Process: com.android.keychain, PID: 4975
E/AndroidRuntime( 4975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4975): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4975): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4975): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4975): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4975): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4975): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4991 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4975): killProcess, pid=4975
D/Process ( 4975): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1449758476542.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
I/ActivityManager(  906): Recipient 4975
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4975) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4991): getInstance(Context context)
D/AppTag  ( 4991): getInstance(Context context)
D/AppTag  ( 4991): onCreate()
D/PMS     (  906): acquireWL(426f4f40): PARTIAL_WAKE_LOCK  AsyncService 0x1 4076 10160 null
D/PMS     (  906): releaseWL(426f4f40): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4115): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2170): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2170): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2170): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2170): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2170): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2170): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 2170): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2170): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d1f1230
W/dalvikvm( 2170): threadid=48: thread exiting with uncaught exception (group=0x41700e30)
E/SQLiteLog( 1360): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1360): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f83d60
W/dalvikvm( 1360): threadid=1: thread exiting with uncaught exception (group=0x41700e30)
E/SQLiteLog( 2170): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2170): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6591a948
I/LocationSettingsChecker( 2170): Removing dialog suppression flag for package com.test.thalitest
E/DriveAsyncService( 2170): disk I/O error (code 3850)
E/DriveAsyncService( 2170): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2170): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2170): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2170): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2170): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2170): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2170): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2170): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2170): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2170): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2170): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2170): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2170): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2170): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2170): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2170): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  906): Delay finish: com.google.android.gms/.gcm.GcmPackageTracker$GcmPackageChangeReceiver

```
