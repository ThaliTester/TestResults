#### Test 55311151a2306df_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  907): Waited long enough for: ServiceRecord{42461e48 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4468): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4468): ====startRecUseTime====
D/htc.customization.log.level( 4468):  is 
W/CustomizationLogLevel( 4468): Level value is invalid, use default level 2
D/CustomizationManager( 4468):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4468): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4468): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4468): Parsing tag category name = system
I/CustomizationCIDLoader( 4468): Parsing tag category name = application
I/CustomizationCIDLoader( 4468): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4468): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4468): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4468): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4468): Parsing tag category name = Settings
D/CustomizationManager( 4468):  Read CID file spent 0.102 (s)
D/CustomizationManager( 4468):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 4468): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4468): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4468): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4468): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4468
D/PMS     (  907): acquireHCC(424c0168): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(421da5f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1112523656
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ca5810
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  907): acquireWL(41e8a120): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4479 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4479): Binding Chromium to main looper Looper (main, tid 1) {41b64408}
I/LibraryLoader( 4479): Expected native library version number "",actual native library version number ""
I/chromium( 4479): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4479): Initializing chromium process, renderers=0
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42458120:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4479): 1102552640: getState(). Returning 12
D/PMS     (  907): acquireWL(42574330): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): acquireWL(424d8a50): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): releaseWL(42574330): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4479): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4479): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4479): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4479): Local Branch: 
I/Adreno-EGL( 4479): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4479): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4479):                  aa63bbd948f41d15fc72f585e
W/chromium( 4479): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4479): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4479): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4479): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4479): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4479): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4479): CordovaWebView is running on device made by: HTC
,W/AwContents( 4479): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1271
,W/ResourceType( 4479): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManagerService(  907): Enable input method client, pid=4479
I/InputMethodManager( 4479): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bab530, mServedView=org.apache.cordova.engine.SystemWebView{41b71158 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4479): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +298ms
D/PMS     (  907): releaseWL(41e8a120): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4479): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4479): JniHelper::setJavaVM(0x4163b048), pthread_self() = 1663908864
,D/JX-Cordova( 4479): jxcore cordova android initializing
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.624MB for 96598-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.704MB for 144892-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.819MB for 217334-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.996MB for 325996-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 12.269MB for 488990-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 13.277MB for 1100216-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 14.166MB for 1650320-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 15.517MB for 2475476-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 17.544MB for 3713210-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(424c0168): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(421da5f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4479): Initializing JXcore engine
,W/jxcore-log( 4479): JXcore engine is ready
,W/jxcore-log( 4479): Starting JXcore engine
,W/jxcore-log( 4479): Platform android
W/jxcore-log( 4479): 
,W/jxcore-log( 4479): Process ARCH arm
W/jxcore-log( 4479): 
,I/jxcore-log( 4479): JXcore Cordova bridge is ready!
I/jxcore-log( 4479): 
,W/jxcore-log( 4479): JXcore engine is started
,I/chromium( 4479): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  907): releaseWL(424d8a50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42275210
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  907): pid=907, uid=1000
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  907): setLight #0: color=#0
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42275210, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4223ae38
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@427b1a80
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 316ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMS     (  907): OOBE c monitor 11
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@433a3ac8)
D/PMN     (  907): wakingUp
,I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
I/InputMethodManagerService(  907): Disable input method client, pid=4479
D/PMS     (  907): acquireWL(424c19e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  907): releaseWL(424c19e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): acquireWL(44227ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(44227ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20824 delay=15s
D/MtpService( 2721): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1253): applyRouting - 0
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2721): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting -2
D/PMS     (  907): acquireWL(4413d520): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
D/PMS     (  907): releaseWL(4413d520): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1117): stop update clock
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
I/wpa_supplicant( 1163): SET_SCREEN_ON:On
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4529 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  373): ParamSet string: screen_state=on
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  907): updateScreenOn: false
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  907): acquireWL(43d23c38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(43baf110): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4529 1000 null
D/PMS     (  907): releaseWL(43d23c38): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(432facb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(432facb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOn: 1452155886199
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOn: 1452155886199
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4223ae38
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4223ae38, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@427b1a80
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(433598e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20824 mDataStallAlarmIntent=PendingIntent{43cf00f8: PendingIntentRecord{425ac2c8 android broadcastIntent}}
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/SmartSyncUtils( 4529): getMobilePolicyEnabled, result = true
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): SET_SCREEN_ON:Off
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1163): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=3890
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
D/PMS     (  907): acquireWL(437fc308): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/PMS     (  907): releaseWL(43baf110): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  907): Killing 3890:com.google.android.music:main/u0a154 (adj 15): empty #17
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1298): receiver - intent: android.intent.action.USER_PRESENT
V/SRS_Proc(  373): ParamSet string: screen_state=off
,D/AutoSetting( 1298): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3835): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3835): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3835): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3835): Cust_ConnectToPC   : spcsc>false
D/        ( 3835): Cust_ConnectToPC   : IPT>true
D/        ( 3835): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3835): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3835): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3835): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3835): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/ActivityManager(  907): Recipient 3890
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 3890): Died!
,D/NetworkPolicy(  907): updateScreenOn: false
D/ContactMessageStore( 1240): start background delete task...
,I/PSReceiver( 3835): onReceive:android.intent.action.USER_PRESENT
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 3835): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3835): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3835):  defaultType:0
W/ContextImpl( 3835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): releaseWL(437fc308): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
I/jxcore-log( 4479): Toggling radios to true
I/jxcore-log( 4479): 
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/BluetoothAdapter( 4479): enable(): BT is already enabled..!
,D/WifiManager( 4479): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1102
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiManager( 4479): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
,D/WifiManager( 4479): reconnect: Base Package Name=com.test.thalitest, uid=10389
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): TDLS: Tear down peers
I/wpa_supplicant( 1163): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4479): Radios toggled
I/jxcore-log( 4479): 
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4479, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4479): Received device characteristics:
I/jxcore-log( 4479): Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4479): Bluetooth name: HTC Desire 820
I/jxcore-log( 4479): Device name: HTC-HTC Desire 820
I/jxcore-log( 4479): 
I/jxcore-log( 4479): Perf Test app loaded loaded
I/jxcore-log( 4479): 
,I/Choreographer( 4479): Skipped 77 frames!  The application may be doing too much work on its main thread.
W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/jxcore-log( 4479): check test folder
I/jxcore-log( 4479): 
D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
,I/jxcore-log( 4479): found test : ./testFindPeers.js
I/jxcore-log( 4479): 
,D/SmartSyncUtils( 4529): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,D/AutoSetting( 1298): service - mHandler: cancel location update
,D/AutoSetting( 1298): service -           changes count: 0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1163): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1163): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1163): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8f09bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1163): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1163): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1163): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427b1a80
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427b1a80, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/SensorService(  907): pid=907, uid=1000
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427b1a80, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  907):    returned true
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43c69b00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427b1a80
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): Fast associate: Old scan results
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): State: DISCONNECTED -> SCANNING
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1163): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20825 mDataStallAlarmIntent=null
D/PMS     (  907): acquireWL(43c48b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43c48b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427b1fc8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427b1fc8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
D/PMS     (  907): acquireWL(441230f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
D/ConnectivityService(  907): Provision feature enable=false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
I/jxcore-log( 4479): found test : ./testSendData.js
I/jxcore-log( 4479): 
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3835): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='1'
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOff
D/WISPrService( 3835): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/PMS     (  907): releaseWL(441230f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1163): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1163): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/WifiNative-wlan0(  907):    returned true
D/wpa_supplicant( 1163): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1163): nl80211: Survey data missing
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1163): Sorted scan results
I/wpa_supplicant( 1163): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1163): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1163): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/wpa_supplicant( 1163): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1163): wpa_supplicant_pick_network+
I/wpa_supplicant( 1163): Selecting BSS from priority group 1
I/wpa_supplicant( 1163): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1163): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1163): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1163):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1163):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1163): Start print parameters
I/wpa_supplicant( 1163): wpa_s->wpa_state is 3
I/wpa_supplicant( 1163): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1163): isConcurrentMode() is 0
I/wpa_supplicant( 1163): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1163): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1163): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1163): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1163): wpa_s->reassociate is 1
I/wpa_supplicant( 1163): wpa_s->is_screen_on 0
I/wpa_supplicant( 1163): wpa_s->ifname wlan0
I/wpa_supplicant( 1163): End print parameters
I/wpa_supplicant( 1163): selected network = 1
D/wpa_supplicant( 1163): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8f0b4e8  current_ssid=0x0
D/wpa_supplicant( 1163): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1163): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1163): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1163): check if in concurrent case
I/wpa_supplicant( 1163): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WISPrService( 3835): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1163): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1163): RSN: PMKSA cache search - network_ctx=0xb8f0b4e8 try_opportunistic=0
D/wpa_supplicant( 1163): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1163): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1163): nl80211: Set mode ifindex 22 iftype 2 (STATION)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1163): nl80211: Unsubscribe mgmt frames handle 0xb8f0a718 (mode change)
D/wpa_supplicant( 1163): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8f0a718
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/WISPrService( 3835): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Register frame type=0xd0 nl_handle=0xb8f0a718
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1163): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1163):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1163):   * freq=2412
D/wpa_supplicant( 1163):   * Auth Type 0
D/wpa_supplicant( 1163):   * WPA Versions 0x2
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1163): nl80211: Connect request send successfully
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1779978, pollInterval: 10000
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1163): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1163): reply (238) for get BSS: id=0
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1163): freq=5220
I/wpa_supplicant( 1163): level=-47
I/wpa_supplicant( 1163): tsf=0000000022729945
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG7005g
I/wpa_supplicant( 1163): ====
I/wpa_supplicant( 1163): id=1
I/wpa_supplicant( 1163): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): freq=2412
I/wpa_supplicant( 1163): level=-54
I/wpa_supplicant( 1163): tsf=0000000104181361
I/wpa_supplicant( 1163): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1163): ssid=NG700
I/wpa_supplicant( 1163): ####
V/NativeCrypto( 1361): Read error: ssl=0x66470248: I/O error during system call, Connection timed out
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 22729945, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 104181361, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 2 to mScanResults
V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x66470248: I/O error during system call, Broken pipe
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WifiManager( 1225): getScanResults enter 
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (2) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/libc    (  366): [NET] entry_id:3   entry:0xb8d86108  removed 
D/libc    (  366): [NET] entry_id:4   entry:0xb8d862f0  removed 
D/libc    (  366): [NET] entry_id:1   entry:0xb8d86428  removed 
D/libc    (  366): [NET] entry_id:5   entry:0xb8d85fd8  removed 
D/libc    (  366): [NET] entry_id:2   entry:0xb8d864f0  removed 
D/libc    (  366): [NET] entry_id:6   entry:0xb8d81f88  removed 
D/libc    (  366): *************************
D/libc    (  366): *** DNS CACHE FLUSHED ***
D/libc    (  366): *************************
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/PMS     (  907): acquireWL(433ba958): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1163): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  907): acquireWL(435d3468): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  907): releaseWL(433ba958): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): wpa_supplicant_scan enter
I/wpa_supplicant( 1163): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1163): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1163): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1163): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1163): Failed to initiate AP scan
I/wpa_supplicant( 1163): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  907):    returned true
I//system/bin/ip(  366): RTNETLINK answers: No such process
I/logwrapper(  366): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  907): releaseWL(435d3468): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,W/ResourceType( 4479): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4479): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b71158 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4479): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  907): releaseWL(433598e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1163): nl80211: Connect event
D/wpa_supplicant( 1163): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1163): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1163): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1163): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1163): Add randomness: count=6 entropy=1
I/wpa_supplicant( 1163): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1163): TDLS: Remove peers on association
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1163): EAPOL: enable timer tick
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1163): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1163): Get randomness: len=32 entropy=2
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantSta,teChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8f0a9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1163):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1163): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f9bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1163):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1163): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1163): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1163): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1163): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,E/wpa_supplicant( 1163): wlan0: Connect to SSID: NG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1163): set send_ind_to_ndc = 0
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (1)+,
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1163): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1163): EAPOL authentication completed successfully
I/wpa_supplicant( 1163): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb,
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3835): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3835): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:3
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 1
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 1163): nl80211: Event message available
D/wpa_supplicant( 1163): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1163): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(43d22ac8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425698e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425698e8 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4570 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/PMS     (  907): acquireWL(437f7ab0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(437f7ab0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTING
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4329/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4329/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/wpa_supplicant( 1163): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1163): EAPOL: disable timer tick
,I/MusicStore( 4570): Database version: 95
,W/ContextImpl( 4570): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4570): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4570): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4570, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4570): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 4570): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2721/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4590 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4570/10154)
,D/MediaRouter( 4570): getSelectedRoute
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4570/10154)
I/NetworkMonitor( 4570): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4570, uid=10154, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ACRA    ( 4590): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  907): acquireWL(426d9f70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(426d9f70): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  907): killProcessQuiet, pid=3870
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4590): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,I/ActivityManager(  907): Killing 3870:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ACRA    ( 4590): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4590): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4590): Preparing secondary program dexes.
V/DexLibLoader( 4590): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4590): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4590): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4590): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4590): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4590): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock,
V/DexLibLoader( 4590): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4590): Dex already copied
D/OdexVerifier( 4590): Odex verification is skipped.,
V/DexLibLoader( 4590): Creating class loader
V/DexLibLoader( 4590): Finished creating class loader
V/DexLibLoader( 4590): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4590): Dex already copied
D/OdexVerifier( 4590): Odex verification is skipped.
V/DexLibLoader( 4590): Creating class loader
,V/DexLibLoader( 4590): Finished creating class loader,
V/DexLibLoader( 4590): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4590): Dex already copied
D/OdexVerifier( 4590): Odex verification is skipped.,
V/DexLibLoader( 4590): Creating class loader
,V/DexLibLoader( 4590): Finished creating class loader
V/DexLibLoader( 4590): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4590): Dex already copied
D/OdexVerifier( 4590): Odex verification is skipped.
,V/DexLibLoader( 4590): Creating class loader
,V/DexLibLoader( 4590): Finished creating class loader
,V/DexLibLoader( 4590): Verifying classes from secondary dexes.
,D/DexLibLoader( 4590): DexLibLoader.ensureDexLoaded took 24 ms
,I/ActivityManager(  907): Recipient 3870
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4590): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4590): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4590): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4590): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4590): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4590): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4590): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4590): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4590): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,E/FbInjectorInitializer( 4590): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(43d22ac8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=33 [3][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1163): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  907): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 3835): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42447400
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  366): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(441813c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/fb4a(:<default>):StaticBindingVerifier( 4590): Verify
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=100 [1][1][0]
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  366): RTNETLINK answers: No such file or directory
,I/logwrapper(  366): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  366): RTNETLINK answers: No such process
,I/logwrapper(  366): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(441813c0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4590): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4590): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4590): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4263
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4263:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4263
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/AutoSetting( 1298): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4642 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1298/10055)
D/AutoSetting( 1298): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1298): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1298): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1298): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1298/10055)
,W/fb4a(:<default>):UserScope( 4590): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4590): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4642): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4642): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4642): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4642): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4642/10079)
W/fb4a(:<default>):UserScope( 4590): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4656 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4093
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4093:com.google.android.talk/u0a111 (adj 15): empty #17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4642/10079)
,D/PMS     (  907): acquireWL(43c08548): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4093
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4642/10079)
,D/PMS     (  907): acquireWL(43a87df8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1452155840146 min interval config: 0 actual interval: 49222
I/CheckinService( 2184): Checking schedule, now: 1452155889374 next: 1452155870126
,I/CheckinService( 2184): active receiver: enabled
D/PMS     (  907): releaseWL(43c08548): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4671 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4296
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1452155836333
I/ActivityManager(  907): Killing 4296:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/ActivityManager(  907): Recipient 4296
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
,I/dalvikvm-heap( 4590): Grow heap (frag case) to 9.954MB for 84664-byte allocation
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
E/dalvikvm( 4590): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4590): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4590): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4590): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4671): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4671): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4671): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4671): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/dalvikvm-heap( 4590): Grow heap (frag case) to 9.971MB for 28144-byte allocation
E/dalvikvm( 4590): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4590): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4590): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4590): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/ContextImpl( 4671): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/dalvikvm( 4590): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4590): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4590): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4590): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4590): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4590): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4590): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4590): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4590): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4590): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4590): Grow heap (frag case) to 10.013MB for 39954-byte allocation
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=33 [3][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/dalvikvm-heap( 4590): Grow heap (frag case) to 10.090MB for 79892-byte allocation
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4671/10151)
,V/WebViewChromiumFactoryProvider( 4671): Binding Chromium to main looper Looper (main, tid 1) {41b6a3a0}
,I/LibraryLoader( 4671): Expected native library version number "",actual native library version number ""
I/chromium( 4671): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4671): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(424a0ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,D/PMS     (  907): acquireWL(42307760): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,E/AudioManagerAndroid( 4671): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(424a0ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4671): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4671): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4671): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4671): Local Branch: 
I/Adreno-EGL( 4671): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4671): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4671):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4701 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4671): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4671/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4671/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/dalvikvm-heap( 4590): Grow heap (frag case) to 10.275MB for 75760-byte allocation
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4329
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
I/ActivityManager(  907): Killing 4329:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4701): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4329
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441131b8 u0 ReceiverList{43c99978 4590 com.facebook.katana/10027/u0 remote:433b06f8}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{441131b8 u0 ReceiverList{43c99978 4590 com.facebook.katana/10027/u0 remote:433b06f8}}
I/MultiDex( 4701): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4701): install
,I/MultiDex( 4701): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4701): loading existing secondary dex files
,I/MultiDex( 4701): load found 3 secondary dex files
,I/MultiDex( 4701): install done
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42b41660 u0 ReceiverList{42b41600 4590 com.facebook.katana/10027/u0 remote:42415628}}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4701): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4701): VFY: unable to resolve instance field 36
,W/dalvikvm( 4701): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4701): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/PMS     (  907): acquireWL(43d20d38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43d20d38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4701): Installed default security provider GmsCore_OpenSSL
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,W/Vold    (  356): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4590): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/dalvikvm( 4701): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
W/dalvikvm( 4701): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4701): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4701): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4701): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4701): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4701): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,E/MDM     ( 1225): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2184): Restart initialization of location
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  907): acquireWL(427ba3c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(427ba3c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(43c69b00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,I/WVCdm   (  373): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  373): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/PMS     (  907): acquireWL(43822058): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3931/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/PMS     (  907): releaseWL(43822058): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4642/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4570/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/NativeLibraryUtils( 4701): Install completed successfully. count=14 extracted=0
,I/NetworkMonitor( 4570): type=WIFI subType= reason=null isConnected=true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
D/PMS     (  907): acquireWL(426eca28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(426eca28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2721/10021)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WVCdm   (  373): PrepareKeyRequest: nonce=1663911070
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/AutoSetting( 1298): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/MobileConnectivityChangeReceiver( 4642): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4642): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1298/10055)
D/AutoSetting( 1298): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1298): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1298): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1298): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1298/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4671/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1452155840146 min interval config: 0 actual interval: 49928
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
D/PMS     (  907): acquireWL(437a7f28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437a7f28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  373): CdmEngine::CloseSession
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
I/dalvikvm-heap( 4135): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,I/Adreno-EGL( 4701): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG (),
I/Adreno-EGL( 4701): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4701): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4701): Local Branch: 
I/Adreno-EGL( 4701): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4701): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4701):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4701): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4701): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4701): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4701): Local Branch: 
I/Adreno-EGL( 4701): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4701): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4701):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  373): PrepareKeyRequest: nonce=4213651337
,I/WVCdm   (  373): CdmEngine::CloseSession
,W/Settings( 4701): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4701/10029)
,I/Adreno-EGL( 4701): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4701): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4701): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4701): Local Branch: 
I/Adreno-EGL( 4701): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4701): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4701):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
,D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =9e0e +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 247
D/libc    (  366): [NET]res_nsend:resplen=84
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2184): Sending checkin request (12252 bytes)
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4479): threadid=1: thread exiting with uncaught exception (group=0x41733e30)
,E/AndroidRuntime( 4479): FATAL EXCEPTION: main
E/AndroidRuntime( 4479): Process: com.test.thalitest, PID: 4479
E/AndroidRuntime( 4479): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4479): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4479): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4479): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4479): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4479): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4479): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4479): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4479): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4479): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4479): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4479): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4479): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4479): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4479): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4479): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4479): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4479): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4479): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  907): App crashed! Process: com.test.thalitest
W/ActivityManager(  907):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  907): killProcessQuiet, pid=4352
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,D/Process ( 4479): killProcess, pid=4479
,D/Process ( 4479): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Killing 4352:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4352
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1212): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4479 uid 10389
,I/ActivityManager(  907): Recipient 4479
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.test.thalitest (pid 4479) has died.
,I/WindowState(  907): WIN DEATH: Window{4266ad20 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  907): Client connection lost with reason: 4
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=50 [20][10][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2184): Checking schedule, now: 1452155891881 next: 1452678828875
,I/CheckinService( 2184): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =4a3e +++++
I/CheckinService( 2184): Checking schedule, now: 1452155891912 next: 1452678828875
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
I/CheckinService( 2184): active receiver: disabled
,D/libc    (  366): [NET] NOT IN CACHE
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1452155891919
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(43a87df8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/PMS     (  907): acquireWL(43cb3e10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
,D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =ba64 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 58
D/libc    (  366): [NET]res_nsend:resplen=79
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  366): [NET]res_nsend:resplen=172
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=4
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/PMS     (  907): acquireWL(43971110): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  907): releaseWL(43cb3e10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(43971110): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43d84d98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,W/fb4a(:<default>):UserScope( 4590): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4590): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(43d84d98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=63 [11][7][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4590): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027),
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4590/10027)
,D/PMS     (  907): releaseWL(42307760): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(4395a828): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4570 10154 null
,W/ContextImpl( 4570): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4570, uid=10154, userID:0
,I/MusicLeanback( 4570): Conditions not met for autocaching.
,I/MusicLeanback( 4570): Stop autocaching.
,W/ContextImpl( 4570): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): releaseWL(4395a828): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4671): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1526): service - handleMessage() stop self
,D/AutoSetting( 1526): service - onDestroy() END
,D/AutoSetting( 1526): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4316
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4316:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4316
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1769965, pollInterval: 10000
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4769 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,E/ExternalAccountType( 1345): Unsupported attribute readOnly
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4769): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4769): MmsConfig.loadMmsSettings
,W/dalvikvm( 4769): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4769): VFY: unable to resolve instance field 36
,W/dalvikvm( 4769): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4769): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4769, uid=10111, userID:0
,W/Settings( 4769): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4792 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4769, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4769, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4769, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4769, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4769, uid=10111, userID:0
,D/PMS     (  907): acquireWL(43213db8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4769 10111 null
,D/MessageFrequencyProvider( 4792): onCreate
,V/GetPrviateResource( 4792): GetPrviateResource
,V/GetPrviateResource( 4792): GetPrviateResource
I/[PluginManager]RegisterService( 1298): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1298): handle notify Blinkfeed plugin client changed
,W/PackageManager(  907): Unable to load service info ResolveInfo{424952b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/MmsCustomizationProvider( 4792): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/IcingCorporaProvider( 2820): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/MmsCustomizationProvider( 4792): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/PMS     (  907): acquireWL(42703790): PARTIAL_WAKE_LOCK  AsyncService 0x1 4135 10160 null
D/PMS     (  907): acquireWL(425d41a8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4769): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4769): MmsConfig.loadFromDatabase
,I/dalvikvm-heap( 4135): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  907): releaseWL(425d41a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43213db8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  907): releaseWL(42703790): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ProviderInstaller( 4769): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 4769): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4769): MmsConfig.loadFromResources
D/PMS     (  907): acquireWL(436ae508): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,E/Babel   ( 4769): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4769): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/dalvikvm-heap( 4135): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
,D/Process (  907): killProcessQuiet, pid=4369
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4369:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  907): Recipient 4369
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/MessageCustFlag( 4792): sense_version=6.0
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/BTAccessoryUtil( 4792): createReceiver
I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
D/BTAccessoryUtil( 4792): registerReceiver return intent = null
D/MessageCustFlag( 4792): sku_id=99
W/SystemReader( 4792): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4792): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4792): networkCode: 
,D/MessageCustFlag( 4792): sku_id=99
D/MmsConfig( 4792): SIE smsPri: null
,D/MmsConfig( 4792): networkCode: 
,D/HtcTelephonyCapability( 4792): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4792): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4792): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4792): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(431cf820): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(431cf820): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/PMS     (  907): acquireWL(43baad40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43baad40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43d433d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43d433d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2820): UpdateCorporaTask done [took 465 ms] updated apps [took 465 ms] 
,D/Process (  907): killProcessQuiet, pid=3931
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3931:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3931
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bf6bd0 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(436ae508): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bf6bd0 -
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,D/Messaging( 4792): mNeedToUpdateDate2 start
,D/MmsConfig( 4792): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4792): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4792): 
D/MmsAsyncWorkHandler( 4792): HM tk = 20001
,D/ReportIndicatorCache( 4792): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4792): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b6b548
,I/Messaging( 4792): mccmnc> 
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4792): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4792): [DraftCache/1] refresh
,D/MmsConfig( 4792): networkCode: 
,D/Messaging( 4792): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4792): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4792): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4792): createReceiver
,D/MessageCustFlag( 4792): sense_version=6.0
,D/Jerry   ( 4792): start to preload cursor >>>>>>>
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1240): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1240): Update uri=content://mms, match=0
V/MmsProvider( 1240): selection=st=129 AND m_type!=134
,D/Messaging( 4792): mNeedToUpdateDate2: false
D/Messaging( 4792): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4792): TransactionService is going to be woken up.
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,V/TransactionService( 4792): 1-Creating TransactionService
V/TransactionService( 4792): onStartCommand: 1
,D/MmsSystemEventReceiver( 4792): unRegisterForConnectionStateChanges
V/TransactionService( 4792): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4792): Loading previous transactions.
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): sku_id=99
D/Messaging( 4792): ViewCache CreatePreload
,D/Messaging( 4792): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4792): _has_set_default_values_2=true
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1240): device_type: 1
,D/MsgPreferenceUtils( 4792): def_index: 0
D/TransactionService( 4792): Force set service start id to 1
V/TransactionService( 4792): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4792): unRegisterForConnectionStateChanges
,D/TransactionService( 4792): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4792): Destroying TransactionService
,D/DraftCache( 4792): [DraftCache/481] rebuildCache
,V/TransactionService( 4792): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4792): globalIndex = 1
,D/MsgPreferenceUtils( 4792): phone state: true
D/MsgPreferenceUtils( 4792): sd state: false
,D/MsgPreferenceUtils( 4792): vIndex = 0
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/Jerry   ( 1240): URI_DRAFT
,D/DraftCache( 4792): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4792): [DraftCache/481] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4792): 
D/MmsAsyncWorkHandler( 4792): HM tk = 20002
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4792): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): sku_id=99
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1240): sku_id=99
,I/GAV4    ( 4769): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(442c6360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{427f64f0: PendingIntentRecord{426c1b70 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123740, Int=0
,D/PMS     (  907): acquireWL(4417fc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(442c6360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=50 [6][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(424d1a90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(424d1a90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4417fc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(436fad00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(436fad00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427b4c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(427b21e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(437e3518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms},
,I/VacuumService( 1225): Vacuum at: now=1452155906170 tag=VacuumService
,D/PMS     (  907): releaseWL(427b4c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427b21e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(433bacf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(433bacf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437e3518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425b5de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(425b5de0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(42674ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(42674ba8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(432096b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(432096b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/PMS     (  907): acquireWL(437e9180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4269cbf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4269cbf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1759954, pollInterval: 10000
,D/PMS     (  907): acquireWL(436ee020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437e9180): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(437b5f20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(437b5f20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 5514 seconds from now (1452155906731)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =1319 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 254
D/libc    (  366): [NET]res_nsend:resplen=87
D/libc    (  366): [NET]res_queryN: exit 3, ancount=2
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  366): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/PMS     (  907): releaseWL(436ee020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43bcca70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(43bcca70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(437976a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=36 [11][4][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(437976a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43d1e408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43d1e408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43cf0d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{43cba0d8: PendingIntentRecord{427b2df8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134191, Int=0
,D/PMS     (  907): releaseWL(43cf0d70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1749942, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/AutoSetting( 1298): service - mHandler: update timezone
,D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1526): service - onCreate(),
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1526): service - mHandler: update timezone
D/DotMatrix( 1562): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1526): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1526): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41bbd9a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 6 1 11
,D/AutoSetting( 1298): service - mHandler: update timezone
,D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1526): service - mHandler: update timezone
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/DotMatrix( 1562): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1526): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1526): service - showManualTimeZoneSelector() send notification (single)
,D/AutoSetting( 1298): service - handleMessage() stop self
D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f6f318 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/AutoSetting( 1298): service - handleMessage() quit looper
,D/AutoSetting( 1298): service - onDestroy() END
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  907): acquireWL(425d5278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42430f58: PendingIntentRecord{41d73c08 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142451, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(43635158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(425d5278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  366): [NET] +++++ res_nsend xid =cf32 +++++
D/libc    (  366): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  366): [NET] NOT IN CACHE
,D/libc    (  366): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  366): [NET]res_nsend:resplen=243
,D/libc    (  366): [NET]res_queryN: exit 3, ancount=10
D/libc    (  366): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  366): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 12(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1739927, pollInterval: 10000
,D/Process (  907): killProcessQuiet, pid=4402
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4402:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4402
,D/PMS     (  907): releaseWL(43635158): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42401838 u0 com.htc.htclocationservice/.AutoSettingService}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1729910, pollInterval: 10000
,D/PMS     (  907): acquireWL(42a45aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42a45aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4370df28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4370df28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1719895, pollInterval: 10000
,D/AutoSetting( 1526): service - handleMessage() stop self
,D/AutoSetting( 1526): service - onDestroy() END
,D/AutoSetting( 1526): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4417
,I/ActivityManager(  907): Killing 4417:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4417
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1709881, pollInterval: 10000
,D/PMS     (  907): acquireWL(43ce99a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{43bc5de8: PendingIntentRecord{439b3e70 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174548, Int=0
,D/PMS     (  907): releaseWL(43ce99a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1699866, pollInterval: 10000
,D/PMS     (  907): acquireWL(43be99f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43be99f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(425ec738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cf8b38: PendingIntentRecord{4255c758 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=193817, Int=0
,D/PMS     (  907): acquireWL(431fac90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/PMS     (  907): releaseWL(425ec738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426e2ec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(431fac90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(426e2ec8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1689853, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1679835, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1669818, pollInterval: 10000
,D/PMS     (  907): acquireWL(43281f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43281f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43cd1d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cd1d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1659802, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1649784, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1639770, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43d46090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43d46090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1629756, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1619742, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1609727, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c08b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=277813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c08b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43d42b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43d42b40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1599722, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1589706, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1579692, pollInterval: 10000
,D/wpa_supplicant( 1163): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1163): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1163): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1163): Wireless event: cmd=0x8c02 len=15
I/wpa_supplicant( 1163): WEXT: Custom wireless event: 'TX_FAIL'
I/wpa_supplicant( 1163): Got ENV Dirty
I/wpa_supplicant( 1163): WiFioffload Got ENV Dirty, enabled = 0
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): WiFioffload RSSI = -54, LINKSPEED = 72
I/wpa_supplicant( 1163): WiFioffload: wifi_to_mobile: 0, mobile_avalible: 1, mobile_link_speed: 0, mobile_signal:97, isCon:0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4271b8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4271b8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1569678, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1559669, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1549653, pollInterval: 10000
,D/PMS     (  907): acquireWL(42760c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=337813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42760c50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=4059
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4059:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4059
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43cae408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cae408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1539641, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1529626, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1519610, pollInterval: 10000
,D/PMS     (  907): acquireWL(42b098e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42b098e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1509595, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1499577, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1489562, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4334ceb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397813, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4334ceb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1479544, pollInterval: 10000
,D/PMS     (  907): acquireWL(43cb5168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43cb5168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1469525, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1459510, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c88bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c88bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1449494, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1439478, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1429461, pollInterval: 10000
,D/PMS     (  907): acquireWL(43d1f870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=457813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43d1f870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1419445, pollInterval: 10000
,D/PMS     (  907): acquireWL(433c0ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(433c0ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1409425, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1399408, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c46440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43c46440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1389401, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1379384, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1369366, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(435fa158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(435fa158): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1359347, pollInterval: 10000
,D/PMS     (  907): acquireWL(4364c350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4364c350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1349330, pollInterval: 10000
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1339313, pollInterval: 10000
,D/PMS     (  907): acquireWL(43d555f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d555f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1329302, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1319291, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1309278, pollInterval: 10000
,D/PMS     (  907): acquireWL(441c58b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=577814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.647MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(441c58b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1299263, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1289246, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1279228, pollInterval: 10000
,D/PMS     (  907): acquireWL(43fcf1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43fcf1f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1269213, pollInterval: 10000
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1240): sku_id=99
D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1259199, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1249186, pollInterval: 10000
,D/PMS     (  907): acquireWL(43d4c740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637813, Int=0
,D/PMS     (  907): releaseWL(43d4c740): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1239172, pollInterval: 10000
,D/PMS     (  907): acquireWL(43d35e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d35e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1229158, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1219138, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c971b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43c971b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1209124, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1199108, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1189093, pollInterval: 10000
,D/PMS     (  907): acquireWL(43be1490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43be1490): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1179078, pollInterval: 10000
,D/PMS     (  907): acquireWL(43bb9498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43bb9498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1169062, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1159046, pollInterval: 10000
,D/PMS     (  907): acquireWL(4399d438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4399d438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1149029, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1139008, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1128993, pollInterval: 10000
,D/PMS     (  907): acquireWL(43803780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=757813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43803780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1118977, pollInterval: 10000
,D/PMS     (  907): acquireWL(437eb6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(437eb6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1108961, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1098944, pollInterval: 10000
,D/PMS     (  907): acquireWL(437e07f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(437e07f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1088929, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1078913, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1068897, pollInterval: 10000
,D/PMS     (  907): acquireWL(43747bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=817813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43747bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1058877, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1048861, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1038845, pollInterval: 10000
,D/PMS     (  907): acquireWL(43727398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43727398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1028829, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1018813, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1008796, pollInterval: 10000
,D/PMS     (  907): acquireWL(4339bac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=877814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4339bac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 998781, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 988774, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 978759, pollInterval: 10000
,D/PMS     (  907): acquireWL(4328cd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4328cd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 968743, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 958727, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 948712, pollInterval: 10000
,D/PMS     (  907): acquireWL(42f22790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=937813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42f22790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 938696, pollInterval: 10000
,D/PMS     (  907): acquireWL(425fb500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/BatteryService(  907): n_update end
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(425fb500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 928681, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 918664, pollInterval: 10000
,D/PMS     (  907): acquireWL(41cbf970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(41cbf970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 908646, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 898627, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 888612, pollInterval: 10000
,D/PMS     (  907): acquireWL(41f57498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41f57498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/PMS     (  907): acquireWL(41de0c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41ddece0: PendingIntentRecord{424f6298 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783900, Int=0
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4906 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42555e08: PendingIntentRecord{4257f8e0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452155993844, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{439f3200: PendingIntentRecord{426708e0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452156238066, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{423eeeb8: PendingIntentRecord{423f0c40 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452156714185, Int=900000
,D/PMS     (  907): acquireWL(42379118): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42667658: PendingIntentRecord{441d4e20 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452156786312, Int=0
,W/ContextImpl( 4529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4529): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4529): MY_DEBUG = false
,D/SmartSyncUtils( 4529): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(437adab8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42379118): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncScreenOnOffTimeReceiver( 4529): [updateNmRange] bManual = false
D/PMS     (  907): acquireWL(42668310): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4529 1000 null
,D/PMS     (  907): releaseWL(41de0c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4529): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
I/EventLogService( 2184): Aggregate from 1452155889428 (log), 1452154437970 (data)
D/SmartSyncScreenOnOffTimeReceiver( 4529): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4529): SettingOnTime = 1452232800000, randomSettingOnTime = 1452231514000
D/SmartSyncScreenOnOffTimeReceiver( 4529): SettingOffTime = 1452218400000, randomSettingOffTime = 1452219053000
D/SmartSyncScreenOnOffTimeReceiver( 4529): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4529): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4529): bNightModeTurnOffOnce = false
W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): releaseWL(42668310): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4906/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(437adab8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Process (  907): killProcessQuiet, pid=4450
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4450:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4450
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 878596, pollInterval: 10000
,D/PMS     (  907): acquireWL(441f98c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(441f98c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4269ddd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{43d68eb8: PendingIntentRecord{42671a58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1010085, Int=0
,D/PMS     (  907): acquireWL(4417fa78): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4417fa78): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4269ddd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(434e82e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024872
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025173
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025249
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025252
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025255
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025258
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026718
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026736
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029341
,D/PMS     (  907): releaseWL(434e82e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=18 [116][21][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 868580, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 858571, pollInterval: 10000
,D/PMS     (  907): acquireWL(4277d770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/BatteryService(  907): n_update end
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(4277d770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 848554, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 838537, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 828522, pollInterval: 10000
,D/PMS     (  907): acquireWL(43baf560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43baf560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 818505, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c074a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(43c074a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 808489, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 798473, pollInterval: 10000
,D/PMS     (  907): acquireWL(44273f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(44273f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 788457, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 778440, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 768427, pollInterval: 10000
,D/PMS     (  907): acquireWL(43853910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1117814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43853910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 758409, pollInterval: 10000
,D/PMS     (  907): acquireWL(437c5ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PMS     (  907): releaseWL(437c5ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 748393, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 738375, pollInterval: 10000
,D/PMS     (  907): acquireWL(436be470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(436be470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 728360, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 718345, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 708329, pollInterval: 10000
,D/PMS     (  907): acquireWL(42f54d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1177814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42f54d58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 698314, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 688301, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 678285, pollInterval: 10000
,D/PMS     (  907): acquireWL(44165d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44165d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 668270, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 658257, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 648242, pollInterval: 10000
,D/PMS     (  907): acquireWL(435c77f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.646MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(435c77f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 638227, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 628207, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 618193, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c6f848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43c6f848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 608179, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 598164, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 588150, pollInterval: 10000
,D/PMS     (  907): acquireWL(4271f478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000},
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1297813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4271f478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 578136, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 568121, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 558105, pollInterval: 10000
,D/PMS     (  907): acquireWL(437e0890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(437e0890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 548088, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 538072, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 528056, pollInterval: 10000
,D/PMS     (  907): acquireWL(4274abd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1357813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4274abd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 518041, pollInterval: 10000
,D/PMS     (  907): acquireWL(4381ae50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4381ae50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 508027, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 498012, pollInterval: 10000
,D/PMS     (  907): acquireWL(43be84e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(43be84e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 487996, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 477979, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 467963, pollInterval: 10000
,D/PMS     (  907): acquireWL(42655320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1417813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42655320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 457948, pollInterval: 10000
,D/PMS     (  907): acquireWL(42cab290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42cab290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 447932, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 437915, pollInterval: 10000
,D/PMS     (  907): acquireWL(43bf78b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bf78b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 427900, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 417884, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 407870, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c5b9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1477814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c5b9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 397854, pollInterval: 10000
,D/PMS     (  907): acquireWL(43bde348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(43bde348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 387838, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 377824, pollInterval: 10000
,D/PMS     (  907): acquireWL(43bc4550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bc4550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 367809, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 357794, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 347778, pollInterval: 10000
,D/PMS     (  907): acquireWL(427083b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1537813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427083b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 337764, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 327750, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 317735, pollInterval: 10000
,D/PMS     (  907): acquireWL(436adca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(436adca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 307720, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 297706, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 287692, pollInterval: 10000
,D/PMS     (  907): acquireWL(42696ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1597813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.695MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(42696ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 277676, pollInterval: 10000
,D/PMS     (  907): acquireWL(43c42dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c42dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 267661, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 257645, pollInterval: 10000
,D/PMS     (  907): acquireWL(4379f2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end,
,D/PMS     (  907): releaseWL(4379f2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 247630, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 237615, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 227600, pollInterval: 10000
,D/PMS     (  907): acquireWL(442c6a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1657814, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(442c6a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 217584, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 207567, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 197551, pollInterval: 10000
,D/PMS     (  907): acquireWL(441ead78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(441ead78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 187536, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 177521, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 167504, pollInterval: 10000
,D/PMS     (  907): acquireWL(44102f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1717813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44102f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 157490, pollInterval: 10000
,D/PMS     (  907): acquireWL(44102738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(44102738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 147476, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 137459, pollInterval: 10000
,D/PMS     (  907): acquireWL(43d208e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d208e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 127444, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 117426, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 107411, pollInterval: 10000
,D/PMS     (  907): acquireWL(43ceb078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1777813, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43ceb078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 97395, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 87379, pollInterval: 10000
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 77364, pollInterval: 10000
,D/PMS     (  907): acquireWL(43cb01e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43cb01e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  359): inotify_add_watch failed. (No such file or directory)
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 67349, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 57332, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 47315, pollInterval: 10000
,D/PMS     (  907): acquireWL(4385be58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1837813, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  907): Prepared write state in 37ms
,I/ProcessStatsService(  907): Prepared write state in 24ms
,D/PMS     (  907): releaseWL(4385be58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 37299, pollInterval: 10000
,D/PMS     (  907): acquireWL(4382db08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4382db08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 27282, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 17265, pollInterval: 10000
,D/PMS     (  907): acquireWL(437f95a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(437f95a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 7251, pollInterval: 10000
,D/Finsky  ( 4160): [1] ExperimentsChangeHandler$2.run: Exiting process because of stale process stable experiments
,I/ActivityManager(  907): Recipient 4160
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.vending (pid 4160) has died.
,D/PMS     (  907): acquireWL(437e83a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423e8e98: PendingIntentRecord{423a0fe0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1897813, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437e83a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4949): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4949): ====startRecUseTime====
D/htc.customization.log.level( 4949):  is 
W/CustomizationLogLevel( 4949): Level value is invalid, use default level 2
D/CustomizationManager( 4949):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4949): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4949): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4949): Parsing tag category name = system
I/CustomizationCIDLoader( 4949): Parsing tag category name = application
I/CustomizationCIDLoader( 4949): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4949): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4949): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4949): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4949): Parsing tag category name = Settings
D/CustomizationManager( 4949):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4949):  All configurations done spent 0.153 (s)
W/HtcNativeFlag( 4949): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4949): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4949): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4949): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4949, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=4570
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  907): Killing 4570:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
D/Process (  907): killProcessQuiet, pid=4671
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  907): killProcessQuiet, pid=4656
I/ActivityManager(  907): Killing 4671:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
I/ActivityManager(  907): Killing 4656:com.android.chrome/u0a96 (adj 15): empty for 1803s
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  907): killProcessQuiet, pid=4642
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  907): Killing 4642:com.google.android.setupwizard/u0a79 (adj 15): empty for 1803s
I/ActivityManager(  907): Recipient 4656
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4642
W/PackageSettings(  907): Skipping PackageSetting{42203560 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Recipient 4570
D/MediaRouterService(  907): Client com.google.android.music (pid 4570): Died!
I/ActivityManager(  907): Recipient 4671
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(42561160): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42561160): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1316): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/SQLiteConnectionPool( 2184): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1298): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1298): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/IcingCorporaProvider( 2820): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
W/Parcel  ( 1253): Reading a NULL string not supported here.
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4963 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1345): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(43dbf978): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43dbf978): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43cf0148): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2820): UpdateCorporaTask done [took 371 ms] updated apps [took 371 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{425f2978 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/SQLiteDatabase( 4963): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4963): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4963): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4963): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4963): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4963): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4963): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4963): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4963): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4963): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4963): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4963): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4963): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4963): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4963): 	at dalvik.system.NativeStart.main(Native Method)
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteOpenHelper( 4963): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4963): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4963): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4963): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4963): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4963): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4963): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4963): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4963): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4963): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4963): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4963): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4963): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4963): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4963): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4963): Opened ClientFlag.db in read-only mode
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4982 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4963/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4963/10100)
W/GAV2    ( 4963): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4982): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4982): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4982): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4982): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4982): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4982): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4982): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4982): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4982): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4982): threadid=10: thread exiting with uncaught exception (group=0x41733e30)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4982): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4982): Process: com.android.keychain, PID: 4982
E/AndroidRuntime( 4982): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4982): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4982): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4982): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4982): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4982): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4982): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4982): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4982): killProcess, pid=4982
D/Process ( 4982): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452157694295.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4982
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4982) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5005 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 5005): getInstance(Context context)
D/AppTag  ( 5005): getInstance(Context context)
D/AppTag  ( 5005): onCreate()
I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  907): acquireWL(42de4b20): PARTIAL_WAKE_LOCK  AsyncService 0x1 4135 10160 null
D/PMS     (  907): releaseWL(42de4b20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5023 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
W/GAV2    ( 4963): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/dalvikvm( 5023): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5023, uid=10074, userID:0
D/Finsky  ( 5023): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (5023/10074)
W/dalvikvm( 5023): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 5023): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (5023/10074)
E/RollingFileStream( 5023): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 5023): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 5023): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 5023): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5023): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 5023): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 5023): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5023): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5023): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5023): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/SQLiteDatabase( 5023): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/SQLiteDatabase( 5023): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5023): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5023): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5023): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5023): threadid=27: thread exiting with uncaught exception (group=0x41733e30)
W/Finsky.CrashDetector( 5023): Failed to write crash file cnt=0, ts=0.
W/Finsky.CrashDetector( 5023): java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash804305: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 5023): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/Finsky.CrashDetector( 5023): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/Finsky.CrashDetector( 5023): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/Finsky.CrashDetector( 5023): 	at com.google.android.finsky.CrashDetector.safeWriteCrashFile(CrashDetector.java:169)
W/Finsky.CrashDetector( 5023): 	at com.google.android.finsky.CrashDetector.uncaughtException(CrashDetector.java:97)
W/Finsky.CrashDetector( 5023): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
W/Finsky.CrashDetector( 5023): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
W/Finsky.CrashDetector( 5023): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 5023): 	at libcore.io.Posix.open(Native Method)
W/Finsky.CrashDetector( 5023): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/Finsky.CrashDetector( 5023): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/Finsky.CrashDetector( 5023): 	... 6 more
E/SQLiteDatabase( 5023): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 5023): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5023): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5023): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5023): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 5023): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
E/SQLiteDatabase( 5023): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 5023): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:3082)
E/SQLiteDatabase( 5023): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5023): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5023): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5023): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5023): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5023): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 5023): threadid=28: thread exiting with uncaught exception (group=0x41733e30)
E/ActivityManager(  907): App crashed! Process: com.android.vending
E/AndroidRuntime( 5023): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 5023): Process: com.android.vending, PID: 5023
E/AndroidRuntime( 5023): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5023): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5023): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5023): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5023): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/AndroidRuntime( 5023): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/AndroidRuntime( 5023): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 5023): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5023): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5023): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5023): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 5023): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 5023): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/Process ( 5023): killProcess, pid=5023
D/Process ( 5023): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.CrashDetector.uncaughtException:100 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2184): Clearing selected account for com.test.thalitest
I/Icing   ( 2184): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2184): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb21918
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bf6bd0 +
I/Prism.WidgetManager( 1271): onLoadItems() +
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
E/DriveAsyncService( 2184): disk I/O error (code 3850)
E/DriveAsyncService( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2184): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6de04350
E/SQLiteDatabase( 2184): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2184): threadid=50: thread exiting with uncaught exception (group=0x41733e30)
E/PhenotypeInitializer( 2184): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2184): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Recipient 5023
I/ActivityManager(  907): Process com.android.vending (pid 5023) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/Icing   ( 2184): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 2184): Could not init tag ds.tag.deleted
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2184): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2184): Process: com.google.android.gms, PID: 2184
E/AndroidRuntime( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2184): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2184): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2184): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2184): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 2184): killProcess, pid=2184
E/SQLiteDatabase( 2184): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2184): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2184): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2184): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2184): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2184): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2184): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2184): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2184): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2184): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 2184
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms (pid 2184) has died.
D/PMS     (  907): handleWLDeath(43cf0148): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20994ms
E/SQLiteLog( 1361): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1361): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5ca83da8
W/dalvikvm( 1361): threadid=1: thread exiting with uncaught exception (group=0x41733e30)
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
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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

```
