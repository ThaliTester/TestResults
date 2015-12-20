#### Test 506502785b2d2b2_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=164 rxSum=136} preTxRxSum={txSum=164 rxSum=136}
D/WifiDataStallTracker(  910): updateDataStallInfo: NONE
D/WifiDataStallTracker(  910): onDataStallAlarm: tag=19820 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19821 delay=15s
D/PMS     (  910): acquireWL(438c7e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{43980b70: PendingIntentRecord{42643348 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=100165, Int=0
D/PMS     (  910): releaseWL(438c7e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
E/cutils-trace( 4536): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4536): ====startRecUseTime====
D/htc.customization.log.level( 4536):  is 
W/CustomizationLogLevel( 4536): Level value is invalid, use default level 2
D/CustomizationManager( 4536):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4536): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4536): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4536): Parsing tag category name = system
I/CustomizationCIDLoader( 4536): Parsing tag category name = application
I/CustomizationCIDLoader( 4536): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4536): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4536): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4536): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4536): Parsing tag category name = Settings
D/CustomizationManager( 4536):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4536):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4536): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4536): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4536): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4536): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4536
D/PMS     (  910): acquireHCC(440c05a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(440f11f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x62fa6b38 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1120094448
D/PMS     (  910): acquireWL(42678f58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@4206b820
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4547 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4547): Copying FileAsset 0x5c7b3428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4547): Binding Chromium to main looper Looper (main, tid 1) {41b28ee0}
I/LibraryLoader( 4547): Expected native library version number "",actual native library version number ""
I/chromium( 4547): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4547): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(424d3f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): acquireWL(4257fec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426d38b0:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4547): 1102314856: getState(). Returning 12
D/PMS     (  910): releaseWL(424d3f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4547): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4547): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4547): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4547): Local Branch: 
I/Adreno-EGL( 4547): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4547): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4547):                  aa63bbd948f41d15fc72f585e
W/chromium( 4547): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4547): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4547): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4547): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4547): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4547): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4547): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4547): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4547): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4547): CordovaWebView is running on device made by: HTC
,W/AwContents( 4547): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1273
,W/ResourceType( 4547): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4547): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b71418, mServedView=org.apache.cordova.engine.SystemWebView{41b37080 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4547): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +292ms
W/XT9_C   ( 1214): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1214): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1214): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1214): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  910): Enable input method client, pid=4547
,D/PMS     (  910): releaseWL(42678f58): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 71
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/JsMessageQueue( 4547): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4547): JniHelper::setJavaVM(0x41601048), pthread_self() = 1663190552
,D/JX-Cordova( 4547): jxcore cordova android initializing
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.600MB for 144892-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.718MB for 217334-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.897MB for 325996-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 12.166MB for 488990-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 12.573MB for 733480-byte allocation
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420f1388
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420f1388, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4239c4c0
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@4264a530
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 14.020MB for 1650320-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 15.435MB for 2475476-byte allocation
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 330ms
D/NfcService( 1258): ScreenObserver: OFF
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43268ff8)
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
I/InputMethodManagerService(  910): Disable input method client, pid=4547
,D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): applyRouting -2
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  910): wakingUp
D/PMS     (  910): acquireWL(43649dc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  910): releaseWL(43649dc8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
I/WindowManager(  910): No lock screen! windowToken=null
D/PMN     (  910): onScreenOn
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/MtpService( 1972): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1972): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): applyRouting -2
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): acquireWL(43d2c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(43d2c3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): acquireWL(438b35b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
,D/PMS     (  910): releaseWL(438b35b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/AutoSetting( 1371): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
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
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,D/AutoSetting( 1371): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19822 delay=15s
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): SET_SCREEN_ON:On
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): BG scan when screen On
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): Match BG scan, scan!
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  910):    returned true
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1185): nl80211: Event message available
D/TetherSettings( 4366): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/        ( 4366): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4366): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4366): Cust_ConnectToPC   : spcsc>false
D/        ( 4366): Cust_ConnectToPC   : IPT>true
D/        ( 4366): Cust_ConnectToPC   : Singel_USB>false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/Settings( 4366): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4366): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4366): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4366): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4366): onReceive:android.intent.action.USER_PRESENT
,V/SRS_Proc(  371): ParamSet string: screen_state=on
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
,W/ContextImpl( 4366): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/SmartNS_PSService( 4366): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4366): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4366):  defaultType:0
,I/ClockThread( 1119): stop update clock
D/NetworkPolicy(  910): updateScreenOn: false
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4598 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): acquireWL(44173930): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(44173930): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4327ec78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4327ec78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1782): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): onScreenOn: 1450579267599
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1782): onScreenOn: 1450579267599
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4239c4c0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4239c4c0, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@4264a530
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): acquireWL(43c8d270): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
,D/PMS     (  910): releaseHCC(440c05a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(440f11f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19822 mDataStallAlarmIntent=PendingIntent{43e7b2c0: PendingIntentRecord{42643348 android broadcastIntent}}
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
D/PMS     (  910): acquireWL(4320ec60): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,D/SmartSyncUtils( 4598): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(4372d720): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4598 1000 null
,D/PMS     (  910): releaseWL(4372d720): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4598): getMobilePolicyEnabled, result = true
,D/Process (  910): killProcessQuiet, pid=3916
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3916:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 17.536MB for 3713210-byte allocation
,I/ActivityManager(  910): Recipient 3916
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/jxcore-log( 4547): Initializing JXcore engine
,W/jxcore-log( 4547): JXcore engine is ready
,W/jxcore-log( 4547): Starting JXcore engine
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{4232b7f8 u0 com.test.thalitest/.MainActivity t2}
,W/jxcore-log( 4547): Platform android
W/jxcore-log( 4547): 
,W/jxcore-log( 4547): Process ARCH arm
W/jxcore-log( 4547): 
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): SET_SCREEN_ON:Off
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 97
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/ContactMessageStore( 1242): start background delete task...
,D/NetworkPolicy(  910): updateScreenOn: false
D/ContactMessageStore( 1242): size: 0 , 0
D/ContactMessageStore( 1242): Background delete complete
,W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4598): isEpsOn(), nState = 0
D/SmartSyncUtils( 4598): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4598): getMobilePolicyEnabled, result = true
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4264a530
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4264a530, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4264a530, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4264a530
D/WifiService(  910): New client listening to asynchronous messages
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426af3e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426af3e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1371): service - mHandler: cancel location update
,D/AutoSetting( 1371): service -           changes count: 0
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(43343c80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43343c80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(437706a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1782): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1782): onScreenOff
D/PMS     (  910): releaseWL(437706a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 4547): JXcore Cordova bridge is ready!
I/jxcore-log( 4547): 
,W/jxcore-log( 4547): JXcore engine is started
,I/Choreographer( 4547): Skipped 149 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4547): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/ResourceType( 4547): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4547): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b37080 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  910): releaseWL(4257fec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  910): releaseWL(43c8d270): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(4320ec60): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1185): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1185): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 1185): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-89
D/wpa_supplicant( 1185): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1185): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1185): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1185): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1185): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 9
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1185): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1185): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1185): p2p0: Updating scan results from sibling
E/wpa_supplic,ant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1185): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1185): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 1185): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-89
D/wpa_supplicant( 1185): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1185): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1185): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1185): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1185): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1185): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (641) for get BSS: id=0
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-49
I/wpa_supplicant( 1185): tsf=0000000104774929
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=1
I/wpa_supplicant( 1185): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-57
I/wpa_supplicant( 1185): tsf=0000000104774949
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1185): ssid=01ABC
I/wpa_supplicant( 1185): ====,
I/wpa_supplicant( 1185): id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-57
I/wpa_supplicant( 1185): tsf=0000000104774959
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=3
I/wpa_supplicant( 1185): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1185): freq=2462
,I/wpa_supplicant( 1185): level=-87
I/wpa_supplicant( 1185): tsf=0000000104774968
I/wpa_supplicant( 1185): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=UPC Wi-Free
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=4
I/wpa_supplicant( 1185): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1185): freq=2462
I/wpa_supplicant( 1185): level=-89
I/wpa_supplicant( 1185): tsf=0000000104774979
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=UPC5999698
I/wpa_supplicant( 1185): ####
,D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  910): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@4380bde8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4380bde8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4380bde8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 104774929, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 104774949, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 104774959, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 104774968, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  910): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 104774979, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): add 5 to mScanResults
,V/ScoreHelper(  910): Only print Top 10 in ApScanList
V/ScoreHelper(  910):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-87], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1226): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (5) end of scan result ==
,D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (5) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,I/jxcore-log( 4547): Toggling radios to true
I/jxcore-log( 4547): 
,D/BluetoothAdapter( 4547): enable(): BT is already enabled..!
,D/WifiManager( 4547): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1270
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
,W/Settings:Agent(  910): << traceCallingStack(): 1(ms)
D/WifiManager( 4547): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4547): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): TDLS: Tear down peers
,I/wpa_supplicant( 1185): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4547): Radios toggled
I/jxcore-log( 4547): 
D/WifiService(  910): setWifiEnabled: true pid=4547, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  910): New client listening to asynchronous messages
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4547): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4547): 
I/jxcore-log( 4547): Perf Test app loaded loaded
I/jxcore-log( 4547): 
I/jxcore-log( 4547): check test folder
I/jxcore-log( 4547): 
I/jxcore-log( 4547): found test : ./testFindPeers.js
I/jxcore-log( 4547): 
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1185): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1185): TDLS: Remove peers on disassociation
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7a9cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1185): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa,_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(43c1aca8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910):    returned true
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,I/jxcore-log( 4547): found test : ./testSendData.js
I/jxcore-log( 4547): 
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1185): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1185): Start print parameters
I/wpa_supplicant( 1185): wpa_s->wpa_state is 0
I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 1
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0xb7a9e4e8  current_ssid=0x0
D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb7a9e4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19823 mDataStallAlarmIntent=null
I/wpa_supplicant( 1185): State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
,D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb7a9d718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a9d718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
,D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/UsbnetStateTracker(  910): isAvailable+-
,D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
,D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WISPrService( 4366): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiNative-wlan0(  910):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WISPrService( 4366): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 1351): Read error: ssl=0x65f9f558: I/O error during system call, Connection timed out
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 75
,D/wpa_supplicant( 1185): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/WifiService(  910): New client listening to asynchronous messages
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(433715f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
,V/NativeCrypto( 1351): SSL shutdown failed: ssl=0x65f9f558: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:4   entry:0xb75a0220  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb759fd90  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb75a0860  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb75a02f8  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb759ff30  removed 
,D/libc    (  363): [NET] entry_id:1   entry:0xb75a0428  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb759fe40  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb75a00e8  removed 
D/libc    (  363): [NET] entry_id:10   entry:0xb759ffe0  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WISPrService( 4366): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
,D/WISPrService( 4366): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  910): acquireWL(43561ad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1351/10029)
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1185): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1185): Failed to initiate AP scan
I/wpa_supplicant( 1185): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  910): releaseWL(433715f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(43561ad0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1185): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Add randomness: count=16 entropy=10
I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): TDLS: Remove peers on association
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
I/chromium( 4547): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1185): EAPOL: enable timer tick
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1185): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): Get randomness: len=32 entropy=11
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7a9d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f91b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    broadcast key
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1185): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1185): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1185): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1185): set send_ind_to_ndc = 0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1185): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1185): EAPOL authentication completed successfully
I/wpa_supplicant( 1185): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  910): This record is existed, only update it...
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/WISPrService( 4366): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4366): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(4426b6c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 1
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1185): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  910):    returned null
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1,
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42402be0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42402be0 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4638 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  910): acquireWL(4422f080): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(4422f080): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTING
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false,
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,D/CaptivePortalTracker(  910): NoActiveNetworkState
I/Tethering(  910): ipv4Default null
,I/Tethering(  910): No IPv4 upstream interface, giving up.
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3,
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4420/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4420/10100)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/wpa_supplicant( 1185): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1185): EAPOL: disable timer tick
,I/MusicStore( 4638): Database version: 95
,W/ContextImpl( 4638): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4638): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4638): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4638, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4638): Registered
,I/MediaRouter( 4638): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4638/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1972/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4658 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4638): getSelectedRoute
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4638/10154)
I/NetworkMonitor( 4638): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4638, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ACRA    ( 4658): ACRA is enabled for com.facebook.katana, intializing...
D/PMS     (  910): acquireWL(43cf2708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/ACRA    ( 4658): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4658): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/Process (  910): killProcessQuiet, pid=4307
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): releaseWL(43cf2708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  910): Killing 4307:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4307
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4658): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4658): Preparing secondary program dexes.
V/DexLibLoader( 4658): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4658): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4658): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4658): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4658): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4658): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4658): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4658): Dex already copied
D/OdexVerifier( 4658): Odex verification is skipped.
V/DexLibLoader( 4658): Creating class loader
V/DexLibLoader( 4658): Finished creating class loader
V/DexLibLoader( 4658): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4658): Dex already copied
D/OdexVerifier( 4658): Odex verification is skipped.
V/DexLibLoader( 4658): Creating class loader
V/DexLibLoader( 4658): Finished creating class loader
V/DexLibLoader( 4658): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4658): Dex already copied
D/OdexVerifier( 4658): Odex verification is skipped.
V/DexLibLoader( 4658): Creating class loader
V/DexLibLoader( 4658): Finished creating class loader
V/DexLibLoader( 4658): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4658): Dex already copied
D/OdexVerifier( 4658): Odex verification is skipped.
V/DexLibLoader( 4658): Creating class loader
V/DexLibLoader( 4658): Finished creating class loader
V/DexLibLoader( 4658): Verifying classes from secondary dexes.
D/DexLibLoader( 4658): DexLibLoader.ensureDexLoaded took 22 ms
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(4426b6c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  910): WAN detection
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
,D/WISPrService( 4366): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@424ae6e0
,D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1185): Change stage from stage0 to stage3
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
,D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
,D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(423a9560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [1][0][0]
D/PMS     (  910): releaseWL(423a9560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/dalvikvm( 4658): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4658): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4658): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4658): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4658): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4658): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=4329
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4329:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4329
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1371): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4709 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1371): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1371): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
D/AutoSetting( 1371): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1371): service - onStartCommand() check timezone in 30000
,D/PMS     (  910): releaseWL(43c1aca8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,W/fb4a(:<default>):UserScope( 4658): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4658): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/MobileConnectivityChangeReceiver( 4709): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4709): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4709): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4709): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4658): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4723 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 3403:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/Process (  910): killProcessQuiet, pid=3403
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4709/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4709/10079)
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
I/ActivityManager(  910): Recipient 3403
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3958/10053)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,D/AccTypeManager( 1336): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(43cb07d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4638/10154)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4709/10079)
I/NetworkMonitor( 4638): type=WIFI subType= reason=null isConnected=true
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4420/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
W/AccTypeManager( 1336): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1336): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4709/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4420/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43cf30f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43cf30f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(43cb07d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/PMS     (  910): acquireWL(4327ca08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1450579217882 min interval config: 0 actual interval: 55195
D/PMS     (  910): acquireWL(43c93e10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4327ca08): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/ExternalAccountType( 1336): Unsupported attribute readOnly
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4741 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=4343
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CheckinService( 2183): Checking schedule, now: 1450579273098 next: 1450579247855
,I/CheckinService( 2183): active receiver: enabled
I/ActivityManager(  910): Killing 4343:com.android.settings:remote/1000 (adj 15): empty #17
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2183, uid=10029, userID:0
,E/dalvikvm( 4658): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4658): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/CheckinService( 2183): Preparing to send checkin request
,I/EventLogService( 2183): Accumulating logs since 1450579213275
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 9.958MB for 84664-byte allocation
E/dalvikvm( 4658): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4658): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4658): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4658): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4658): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4658): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4658): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4658): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4658): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4741): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4741): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4741): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4741): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 9.971MB for 28144-byte allocation
,W/dalvikvm( 4658): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4658): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4658): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4658): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4658): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4658): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4658): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4741): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  910): Recipient 4343
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 10.014MB for 39954-byte allocation
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 10.090MB for 79892-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4741/10151)
,V/WebViewChromiumFactoryProvider( 4741): Binding Chromium to main looper Looper (main, tid 1) {41b30220}
,I/LibraryLoader( 4741): Expected native library version number "",actual native library version number ""
,I/chromium( 4741): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4741): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(43cd1d68): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  910): acquireWL(441236f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4741): BLUETOOTH permission is missing!
D/PMS     (  910): releaseWL(43cd1d68): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4741): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4741): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4741): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4741): Local Branch: 
I/Adreno-EGL( 4741): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4741): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4741):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4771 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4741): Starting up...
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4741/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4741/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/Process (  910): killProcessQuiet, pid=4069
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4069:com.google.android.gm/u0a107 (adj 15): empty #17
,W/dalvikvm( 4771): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
I/dalvikvm-heap( 4658): Grow heap (frag case) to 10.275MB for 75760-byte allocation
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4771): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
I/MultiDex( 4771): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4771): install
,I/MultiDex( 4771): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/ActivityManager(  910): Recipient 4069
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/MultiDex( 4771): loading existing secondary dex files
,I/MultiDex( 4771): load found 3 secondary dex files
,I/MultiDex( 4771): install done
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{438c8788 u0 ReceiverList{438c86e8 4658 com.facebook.katana/10027/u0 remote:438c5550}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{438c8788 u0 ReceiverList{438c86e8 4658 com.facebook.katana/10027/u0 remote:438c5550}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44088a18 u0 ReceiverList{440889b8 4658 com.facebook.katana/10027/u0 remote:43227100}}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1972/10021)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4771): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/AutoSetting( 1506): service - handleMessage() stop self
,W/dalvikvm( 4771): VFY: unable to resolve instance field 36
,W/dalvikvm( 4771): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,V/JNIHelp ( 4771): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/AutoSetting( 1506): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4100
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4100:com.google.android.talk/u0a111 (adj 15): empty #17
D/PMS     (  910): acquireWL(43f97068): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43f97068): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1371): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4709): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4709): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
D/AutoSetting( 1371): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1371): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1371): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1371): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4741/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4658): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/ProviderInstaller( 4771): Installed default security provider GmsCore_OpenSSL
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4658): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4658): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,W/dalvikvm( 4771): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4771): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1226): callingUid 10029, callindPid: 1226
D/LocationInitializer( 2183): Restart initialization of location
,W/dalvikvm( 4771): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4771): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4771): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4771): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4771): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  910): Recipient 4100
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/MDM     ( 1226): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1351): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1351): Proximity feature is not enabled.
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
D/PMS     (  910): acquireWL(43b26108): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43b26108): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4771): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=888034889
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=555879166
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4771): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4771): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4771): Local Branch: 
I/Adreno-EGL( 4771): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4771): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4771):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4771): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4771): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4771): Local Branch: 
I/Adreno-EGL( 4771): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4771): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4771):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4771): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4771): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4771): Local Branch: 
I/Adreno-EGL( 4771): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4771): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4771):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4771): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4771/10029)
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bf33 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2183): [NET] getaddrinfo-, 1
D/libc    ( 2183): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6624 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 99
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,W/dalvikvm( 4547): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4547): threadid=1: thread exiting with uncaught exception (group=0x416f9e30)
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,E/AndroidRuntime( 4547): FATAL EXCEPTION: main
E/AndroidRuntime( 4547): Process: com.test.thalitest, PID: 4547
E/AndroidRuntime( 4547): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4547): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4547): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4547): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4547): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4547): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4547): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4547): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4547): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4547): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4547): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4547): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4547): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4547): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4547): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4547): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4547): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4547): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4547): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  910): App crashed! Process: com.test.thalitest
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,W/ActivityManager(  910):   Force finishing activity com.test.thalitest/.MainActivity
D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/Process (  910): killProcessQuiet, pid=4389
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  910): Killing 4389:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/Process ( 4547): killProcess, pid=4547
,D/Process ( 4547): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Recipient 4389
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinTask( 2183): Sending checkin request (12201 bytes)
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1214): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4547 uid 10389
,I/ActivityManager(  910): Recipient 4547
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.test.thalitest (pid 4547) has died.
,I/WindowState(  910): WIN DEATH: Window{424606d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  910): Client connection lost with reason: 4
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=29 [17][5][0]
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2183): Checking schedule, now: 1450579275728 next: 1451102212724
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,D/CheckinService( 2183): Recording last checkin time for package unspecified as 1450579275765
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(43c93e10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/PMS     (  910): acquireWL(441b1c00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/GCM     ( 1351): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1351): [NET] getaddrinfo-, 1
,D/libc    ( 1351): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d1fe +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,W/fb4a(:<default>):UserScope( 4658): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4658): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 223
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1351): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
,D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4658): Called registerBroadcastReceiver twice.
,D/PMS     (  910): acquireWL(440fa030): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  910): releaseWL(441b1c00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(440fa030): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440d8e98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(440d8e98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/PMS     (  910): releaseWL(441236f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(43cc51b8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4638 10154 null
,W/ContextImpl( 4638): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4638, uid=10154, userID:0
,I/MusicLeanback( 4638): Conditions not met for autocaching.
,I/MusicLeanback( 4638): Stop autocaching.
D/PMS     (  910): releaseWL(43cc51b8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4638): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4741): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=3958
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3958:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3958
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  910): acquireWL(41f8aa68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{43c86278: PendingIntentRecord{4253ac18 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=118238, Int=0
,D/PMS     (  910): acquireWL(41cd5b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  910): releaseWL(41f8aa68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms},
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(42c2faf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1336): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4836 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
D/PMS     (  910): releaseWL(42c2faf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1336): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1336): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PMS     (  910): releaseWL(41cd5b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,E/ExternalAccountType( 1336): Unsupported attribute readOnly
,D/PMS     (  910): acquireWL(4407f760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(4407f760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4237dbd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): acquireWL(42745108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42618ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4836): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4836): MmsConfig.loadMmsSettings
,I/VacuumService( 1226): Vacuum at: now=1450579283791 tag=VacuumService
,W/dalvikvm( 4836): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4836): VFY: unable to resolve instance field 36
,W/dalvikvm( 4836): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  910): releaseWL(4237dbd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,V/JNIHelp ( 4836): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4864 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,D/PMS     (  910): releaseWL(42618ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425f79e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4836, uid=10111, userID:0
,W/Settings( 4836): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,D/MessageFrequencyProvider( 4864): onCreate
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
,V/GetPrviateResource( 4864): GetPrviateResource
,V/GetPrviateResource( 4864): GetPrviateResource
,D/MmsCustomizationProvider( 4864): query uri: content://htc-mms-customization/mms-ua/ua_string
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
,D/MmsCustomizationProvider( 4864): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4836): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4836): MmsConfig.loadFromDatabase
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
D/PMS     (  910): releaseWL(425f79e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4836, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4836, uid=10111, userID:0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/Babel   ( 4836): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4836): MmsConfig.loadFromResources
,E/Babel   ( 4836): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4836): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  910): acquireWL(4397a548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4836, uid=10111, userID:0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4836, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4836, uid=10111, userID:0
,I/ProviderInstaller( 4836): Installed default security provider GmsCore_OpenSSL
D/PMS     (  910): acquireWL(440f45d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4836 10111 null
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
I/[PluginManager]RegisterService( 1371): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1371): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2885): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PMS     (  910): releaseWL(4397a548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/MessageCustFlag( 4864): sense_version=6.0,
,D/BTAccessoryUtil( 4864): createReceiver
,D/BTAccessoryUtil( 4864): registerReceiver return intent = null
D/MessageCustFlag( 4864): sku_id=99
,W/SystemReader( 4864): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  910): releaseWL(440f45d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  910): killProcessQuiet, pid=4420
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Messaging( 4864): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4864): networkCode: 
D/MessageCustFlag( 4864): sku_id=99
D/MmsConfig( 4864): SIE smsPri: null
,D/MmsConfig( 4864): networkCode: 
D/PMS     (  910): acquireWL(4409bf58): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Killing 4420:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/HtcTelephonyCapability( 4864): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4864): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4864): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4864): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  910): Recipient 4420
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): releaseWL(4409bf58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(43df9d28): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425a6f88): PARTIAL_WAKE_LOCK  AsyncService 0x1 3620 10160 null
,D/PMS     (  910): releaseWL(425a6f88): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(43df9d28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  910): acquireWL(43c61570): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43c61570): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43b27708): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): releaseWL(43b27708): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  910): acquireWL(439aeeb8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(439aeeb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
D/PMS     (  910): acquireWL(441ea8a0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2885): UpdateCorporaTask done [took 715 ms] updated apps [took 715 ms] 
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bbcd10 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
I/ActivityManager(  910): Resuming delayed broadcast
,W/PackageManager(  910): Unable to load service info ResolveInfo{43710900 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bbcd10 -
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Messaging( 4864): mNeedToUpdateDate2 start
,D/MmsConfig( 4864): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4864): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4864): 
D/MmsAsyncWorkHandler( 4864): HM tk = 20001
D/ReportIndicatorCache( 4864): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4864): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b31478
,I/Messaging( 4864): mccmnc> 
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/DraftCache( 4864): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4864): [DraftCache/1] refresh
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4864): networkCode: 
,D/Messaging( 4864): ViewCache CreatePreloadOnlyConversationList
D/PMS     (  910): releaseWL(441ea8a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 4864): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4864): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4864): createReceiver
,D/MessageCustFlag( 4864): sense_version=6.0
,D/Jerry   ( 4864): start to preload cursor >>>>>>>
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1242): sku_id=99
,D/TelephUtils( 1242): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
V/MmsProvider( 1242): Update uri=content://mms, match=0
,V/MmsProvider( 1242): selection=st=129 AND m_type!=134
,D/DraftCache( 4864): [DraftCache/481] rebuildCache
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63,
D/MmsSmsV2Provider( 1242):  phoneType = -1
D/Messaging( 4864): Reset downloading state: 0
V/MmsSystemEventReceiver( 4864): TransactionService is going to be woken up.
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4864): mNeedToUpdateDate2: false
,V/TransactionService( 4864): 1-Creating TransactionService
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/MmsSmsV2Provider( 1242): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
V/TransactionService( 4864): onStartCommand: 1
,D/MmsSystemEventReceiver( 4864): unRegisterForConnectionStateChanges
V/TransactionService( 4864): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4864): Loading previous transactions.
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1242):  phoneType = -1
,D/Messaging( 4864): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1242): URI_DRAFT
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/AccFlag ( 1242): device_type: 1
,D/TransactionService( 4864): Force set service start id to 1
V/TransactionService( 4864): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4864): unRegisterForConnectionStateChanges
D/DraftCache( 4864): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4864): [DraftCache/481] rebuildCache time: 3
,D/MmsAsyncWorkHandler( 4864): 
D/MmsAsyncWorkHandler( 4864): HM tk = 20002
D/TransactionService( 4864): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4864): Destroying TransactionService
D/Messaging( 4864): ViewCache CreatePreload
,D/Messaging( 4864): ViewCache CreatePreloadOnlyMultipleOpsList
D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/TransactionService( 4864): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/AccFlag ( 1242): sku_id=99
,D/Cust_MMSMS( 4864): _has_set_default_values_2=true
,D/TelephUtils( 1242): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1242): sku_id=99
,D/MsgPreferenceUtils( 4864): def_index: 0
,D/MsgPreferenceUtils( 4864): globalIndex = 1
D/MsgPreferenceUtils( 4864): phone state: true
D/MsgPreferenceUtils( 4864): sd state: false
,D/MsgPreferenceUtils( 4864): vIndex = 0
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  910): releaseWL(42745108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a24720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(42a24720): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44188c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(437290e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(437290e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): acquireWL(44128fb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44128fb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(441746c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
,D/LocationProviderProxy(  910): applying state to connected service
,D/PMS     (  910): acquireWL(431976d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(431976d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(441746c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4314cff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44188c18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43ca1020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
D/PMS     (  910): acquireWL(44274188): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44274188): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43ca1020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(442475a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(442475a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1226): Scheduling Phenotype for one-off execution 10644 seconds from now (1450579286796)
,D/GetConfigurationSnapshotOperation( 1226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1226): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9547 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 233
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=8 [12][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(4314cff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440af178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(440af178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440a66f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(440a66f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4836): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(43df2a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-,
D/PMS     (  910): releaseWL(43df2a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43336b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{437708c0: PendingIntentRecord{41f1bf18 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=133495, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  910): releaseWL(43336b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1371): service - mHandler: update timezone
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1506): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1565): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1506): service - mHandler: update timezone
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1506): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1506): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1119): removeNotification.gc:54
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e55ec8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 8 2 11
,D/AutoSetting( 1371): service - mHandler: update timezone
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1506): service - mHandler: update timezone
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/DotMatrix( 1565): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1506): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1506): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1371): service - handleMessage() stop self
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41b47838 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 3 11
,D/AutoSetting( 1371): service - onDestroy() END
,D/AutoSetting( 1371): service - handleMessage() quit looper
,D/PMS     (  910): acquireWL(422b4f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41ec3598: PendingIntentRecord{424915f8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141295, Int=0
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(42a4c738): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(422b4f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9488 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(42a4c738): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  910): killProcessQuiet, pid=4436
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4436:com.htc.backup/1000 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4436
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  910): acquireWL(41fb2528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41fb2528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{440869a8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(438cab40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(438cab40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1506): service - handleMessage() stop self
,D/AutoSetting( 1506): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4460
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4460:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4460
,D/PMS     (  910): acquireWL(423a6938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{4289f1d8: PendingIntentRecord{425a5e40 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=168877, Int=0
,D/PMS     (  910): releaseWL(423a6938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(426df778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(426df778): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(423a9648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(423a9648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(426a9998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(426a9998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(42504fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=275121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42504fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(425ba688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425ba688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(41c30250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=335121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(41c30250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42572338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42572338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(41facd20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=395121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(41facd20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(42554298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42554298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(41e11268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=455121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  910): releaseWL(41e11268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(424ce868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(424ce868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(4321d0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4321d0d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(425e3458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=515122, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425e3458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(440f41b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440f41b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43269dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43269dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4234aa50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=575121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4234aa50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42409810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(42409810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1242): sku_id=99
D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<,
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete,
,D/PMS     (  910): acquireWL(426474e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=635121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(426474e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  910): killProcessQuiet, pid=4407
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4407:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4407
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43eb73e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43eb73e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(425dc620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=695122, Int=0
,D/PMS     (  910): releaseWL(425dc620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43be5e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43be5e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4366): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4366): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4366): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4366): Cust_ConnectToPC   : spcsc>false
D/        ( 4366): Cust_ConnectToPC   : IPT>true
,D/        ( 4366): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4366): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4366): Index of the first 1 = 3
W/Settings( 4366): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4366): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4366): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4366): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4366): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 4366): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4366): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4379a120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=755121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4379a120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425a8bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425a8bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42455ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42455ab8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(441dd358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=815121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(441dd358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43bf82e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43bf82e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44260ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(44260ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43267c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=875121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43267c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425ffa08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425ffa08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4418d978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4418d978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424be518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=935121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(424be518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43b3e528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43b3e528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1119): closing low battery warning: level=100
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(431b0820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(431b0820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43fdf2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=995121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43fdf2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43535a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d91b90: PendingIntentRecord{424b8e98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=778400, Int=0
,I/ActivityManager(  910): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4965 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  910): sending alarm PendingIntent{43df9de0: PendingIntentRecord{43df9ac0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4977 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{4252e318: PendingIntentRecord{426ab7a8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450579376114, Int=10800000
,V/AlarmManager(  910): sending alarm PendingIntent{4245a778: PendingIntentRecord{426b5200 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450580096498, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{440a4e20: PendingIntentRecord{43c0ae80 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450580168308, Int=0
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4598): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4598): MY_DEBUG = false
,D/SmartSyncUtils( 4598): isEpsOn(), nState = 0
D/ConnectivityService(  910): Done.
D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): releaseWL(43535a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4598): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4598): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4598): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4598): SettingOnTime = 1450591200000, randomSettingOnTime = 1450589640000
,D/SmartSyncScreenOnOffTimeReceiver( 4598): SettingOffTime = 1450663200000, randomSettingOffTime = 1450663457000
,D/PMS     (  910): acquireWL(441f2328): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4598 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4598): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4598): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4598): bNightModeTurnOffOnce = false
D/PMS     (  910): acquireWL(4409c0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
V/AlarmManager(  910): sending alarm PendingIntent{425304e8: PendingIntentRecord{43978578 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450580168400, Int=0
D/SmartSyncUtils( 4598): getMobilePolicyEnabled, result = true
D/SmartSyncDataLinkTurnOffService( 4598): turnOffMobile bPolicyEnabled = true
,I/ImageRamCache( 4965): create image Cache, size: 31457280.
I/ImageRamCache( 4965): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4965): create image Cache, size: 12582912.
,D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4598): isWifiHotSpotEnabled = false,
D/PMS     (  910): releaseWL(441f2328): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  910): Couldn't get kernel wake lock stats
D/SmartSyncDataLinkTurnOffService( 4598): turnOffMobile bCheckMobileData = false
I/FeedSettings( 4965): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4965): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4965): GroupBudget 60 45 15
D/LocationManagerService(  910): getProviders()=[gps, network]
,D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,I/Prism.ExternalStringMa_( 4965): changeLocale(): en_GB
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4977/10049)
,D/PMS     (  910): releaseWL(4409c0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/LocationManagerService(  910): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4598): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4598): isCharging status = 5
D/SmartSyncDataLinkTurnOffService( 4598): turnOffWifi ui setting = true
D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4598): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4598): isWifiCallingOn, bOn = false
I/Prism.AllAppsOptionsMa_( 4965): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4965): loadGridSize() with Alternative
,D/SmartSyncDataLinkTurnOffService( 4598): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4598): turnOffWifi bWifiConnected = true
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4598/1000)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/libc    ( 4965): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4965): [NET] getaddrinfo-,err=8
D/libc    ( 4965): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4965): [NET] getaddrinfo-, 1
,D/libc    ( 4965): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =672d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/Process (  910): killProcessQuiet, pid=4518
,I/ActivityManager(  910): Killing 4518:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4518
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(441b1c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(441b1c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(440db640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{4246ad98: PendingIntentRecord{42671cf8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1011229, Int=0
,D/PMS     (  910): acquireWL(440db1c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(440db1c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(440db640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440be338): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(440be338): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  363): [NET]Querying server xid =672d (# 1) address = 192.168.1.1 (try=2,nscount=1)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=206
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4965): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=11 [128][15][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0],
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.launcher (4965/10076)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.launcher (4965/10076)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/Process (  910): killProcessQuiet, pid=4709
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4709:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4709
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43f952c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43f952c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43ca17d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1055121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43ca17d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43c9f5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(43c9f5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43b44d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43b44d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43a4d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1115121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43a4d668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Disconnect event
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1185): TDLS: Remove peers on disassociation
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1185): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7a9cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1185): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_s,upplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
,D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19824 mDataStallAlarmIntent=null
D/WifiPerfLock(  910): release()
,D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(438c3f88): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4366): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4366): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,V/NativeCrypto( 1351): Read error: ssl=0x6404e008: I/O error during system call, Connection timed out
,V/NativeCrypto( 1351): SSL shutdown failed: ssl=0x6404e008: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:5   entry:0xb759bc20  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb75a0880  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb75a4d58  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb75a4f60  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb75a0408  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb75a4e08  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(4222e9e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/WISPrService( 4366): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4366): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
D/PMS     (  910): acquireWL(4246aeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1351/10029)
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1185): nl80211: Event message available
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/PMS     (  910): releaseWL(4222e9e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(4246aeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/PMS     (  910): acquireWL(424f2268): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/PMS     (  910): releaseWL(424f2268): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4638/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,I/NetworkMonitor( 4638): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1972/10021)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/AutoSetting( 1371): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5014 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
,D/AutoSetting( 1371): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
,D/AutoSetting( 1371): service - onCreate()
,D/AutoSetting( 1371): service - AddressCache: using context: com.htc.Weather
,D/LocationManagerService(  910): request 4258bc90 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1371): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1371): service - mHandler: cancel location update
,D/AutoSetting( 1371): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 5014): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5014): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5014): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5014): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5014/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5014/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5014/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4741/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/iu.Environment( 2183): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/iu.UploadsManager( 2183): num queued entries: 0
,I/iu.UploadsManager( 2183): num updated entries: 0
,I/iu.SyncManager( 2183): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1185): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1185): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 1185): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-88
I/wpa_supplicant( 1185): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1185): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=17 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=18 entropy=1
D/wpa_supplicant( 1185): Add randomness: count=19 entropy=2
D/wpa_supplicant( 1185): Add randomness: count=20 entropy=3
D/wpa_supplicant( 1185): Add randomness: count=21 entropy=4
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1185): 2: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1185): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1185): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1185): No APs found - clear blacklist and try again
E/wpa_supplicant( 1185): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1185): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1185): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1185): 2: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1185): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1185): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): wlan0: Not restrict scheduled scan for Not WFD, CT3
D/wpa_supplicant( 1185): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1185): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1185): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-87
I/wpa_supplicant( 1185): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-88
I/wpa_supplicant( 1185): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
D/wpa_supplicant( 1185): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=22 entropy=5
D/wpa_supplicant( 1185): Add randomness: count=23 entropy=6
D/wpa_supplicant( 1185): Add randomness: count=24 entropy=7
D/wpa_supplicant( 1185): Add randomness: count=25 entropy=8
D/wpa_supplicant( 1185): Add randomness: count=26 entropy=9
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): clear disabled list - type=1
I/wpa_supplicant( 1185): No suitable network found
W/wpa_supplicant( 1185): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1185): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  910): doBoolean: SET pno 1,
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 75
,D/wpa_supplicant( 1185): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (765) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-57,
I/wpa_supplicant( 1185): tsf=0000000104774959
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=5
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-48
I/wpa_supplicant( 1185): tsf=0000001127074784
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=6
I/wpa_supplicant( 1185): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-57
I/wpa_supplicant( 1185): tsf=0000001127074810
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1185): ssid=01ABC
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=7
,I/wpa_supplicant( 1185): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1185): freq=2462
I/wpa_supplicant( 1185): level=-87
I/wpa_supplicant( 1185): tsf=0000001127074820
I/wpa_supplicant( 1185): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=UPC Wi-Free
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=8
I/wpa_supplicant( 1185): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1185): freq=2462
I/wpa_supplicant( 1185): level=-88
I/wpa_supplicant( 1185): tsf=0000000104774979
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=UPC5999698,
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=9
I/wpa_supplicant( 1185): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1185): freq=2462
I/wpa_supplicant( 1185): level=-91
I/wpa_supplicant( 1185): tsf=0000001127074840
I/wpa_supplicant( 1185): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=UPC Wi-Free
I/wpa_supplicant( 1185): ####
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): == begin of scan result ==
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 104774959, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1127074784, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1127074810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 1127074820, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2462, timestamp: 104774979, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1127074840, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 6 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiStateMachine(  910): == (6) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (1 BSSes),
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1185): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1185): Add randomness: count=27 entropy=10
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1185): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[1] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1185): WPS: AP[2] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1185): wpa_supplicant_pick_network+
I/wpa_supplicant( 1185): Selecting BSS from priority group 1
I/wpa_supplicant( 1185): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1185): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1185): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1185):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1185):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1185): Start print parameters
,I/wpa_supplicant( 1185): wpa_s->wpa_state is 3
,I/wpa_supplicant( 1185): wpa_s->br_have_IP is 0
,I/wpa_supplicant( 1185): isConcurrentMode() is 0
I/wpa_supplicant( 1185): wpa_s->br_mirror_status is 0
,I/wpa_supplicant( 1185): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1185): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1185): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1185): wpa_s->reassociate is 0
I/wpa_supplicant( 1185): wpa_s->is_screen_on 0
I/wpa_supplicant( 1185): wpa_s->ifname wlan0
I/wpa_supplicant( 1185): End print parameters
,I/wpa_supplicant( 1185): selected network = 2
D/wpa_supplicant( 1185): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7a9e4e8  current_ssid=0x0
,D/wpa_supplicant( 1185): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): supplicant attached completed, trigger assoc.,
,D/wpa_supplicant( 1185): wpa_supplicant_set_is_wep_security: 0,
D/wpa_supplicant( 1185): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1185): check if in concurrent case
I/wpa_supplicant( 1185): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1185): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1185): RSN: PMKSA cache search - network_ctx=0xb7a9e4e8 try_opportunistic=0
D/wpa_supplicant( 1185): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1185): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1185): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1185): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1185): nl80211: Unsubscribe mgmt frames handle 0xb7a9d718 (mode change)
D/wpa_supplicant( 1185): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7a9d718
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Register frame type=0xd0 nl_handle=0xb7a9d718
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1185): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1185):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1185):   * freq=2412
D/wpa_supplicant( 1185):   * Auth Type 0
D/wpa_supplicant( 1185):   * WPA Versions 0x2
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1185): nl80211: Connect request send successfully
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1185): reply (765) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-57
I/wpa_supplicant( 1185): tsf=0000001129060502
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=5
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-48
I/wpa_supplicant( 1185): tsf=0000001127074784
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=6
I/wpa_supplicant( 1185): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-57
I/wpa_supplicant( 1185): tsf=0000001127074810
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1185): ssid=01ABC
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=7
I/wpa_supplicant( 1185): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1185): freq=2462
I/wpa_supplicant( 1185): level=-87
I/wpa_supplicant( 1185): tsf=0000001127074820
I/wpa_supplicant( 1185): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=UPC Wi-Free
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=8
I/wpa_supplicant( 1185): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1185): freq=2462
I/wpa_supplicant( 1185): level=-88
I/wpa_supplicant( 1185): tsf=0000000104774979
I/wpa_supplicant( 1185): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=UPC5999698
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=9
I/wpa_supplicant( 1185): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1185): freq=2462
I/wpa_supplicant( 1185): level=-91
I/wpa_supplicant( 1185): tsf=0000001127074840
I/wpa_supplicant( 1185): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1185): ssid=UPC Wi-Free
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1129060502, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1127074784, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 1127074810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 1127074820, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2462, timestamp: 104774979, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 1127074840, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): add 6 to mScanResults
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (6) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1185): nl80211: Connect event
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1185): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/Tethering(  910): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1185): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1185): Add randomness: count=28 entropy=11
I/wpa_supplicant( 1185): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): TDLS: Remove peers on association
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1185): EAPOL: enable timer tick
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1185): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1185): Get randomness: len=32 entropy=12
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7a9d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1185): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/wpa_supplicant( 1185): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f91b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1185):    broadcast key
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1185): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1185): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1185): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1185): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1185): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1185): set send_ind_to_ndc = 0
I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1185): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1185): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1185): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1185): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1185): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1185): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1185): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1185): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1185): EAPOL authentication completed successfully
I/wpa_supplicant( 1185): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1185): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1185): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1185): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false),
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4366): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4366): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1185): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
,D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(43977930): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false,
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1,
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1",
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 1
I/wpa_supplicant( 1185): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1185): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null,
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42402be0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42402be0 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  910): acquireWL(43358150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43358150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1185): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1185): EAPOL: disable timer tick
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16,
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1185): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1185): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [3][0][0]
,D/PMS     (  910): releaseWL(43977930): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  910): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true,
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): WiFi gateway: 0x101a8c0,
I/wpa_supplicant( 1185): htc_wext_set_keepalive +
I/wpa_supplicant( 1185): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1185): getPrivFuncNum +	
I/wpa_supplicant( 1185): getPrivFuncNum -, cmd = 0x8bf6,
I/wpa_supplicant( 1185): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1185): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1185): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1185): htc_wext_set_keepalive - ret = 0
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  910): doBoolean: SCAN TYPE=ONLY
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1185): wpa_supplicant_scan enter
I/wpa_supplicant( 1185): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1185): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1185): Scan req (ret=0) - timeout 30 secs
D/WifiNative-wlan0(  910):    returned true
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
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
,D/WISPrService( 4366): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@424ae6e0
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1185): Change stage from stage0 to stage3,
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
E/NetdConnector(  910): NDC Command {61 resolver setifdns wlan0  192.168.1.1} took too long (803ms)
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
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
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  910): acquireWL(4246bf40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5014/10079)
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(4246bf40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): acquireWL(441a78a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254),
D/PMS     (  910): acquireWL(4416c808): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1450579275765 min interval config: 0 actual interval: 1021759
D/PMS     (  910): releaseWL(441a78a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checking schedule, now: 1450580297536 next: 1450579305724
,I/CheckinService( 2183): active receiver: enabled
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2183, uid=10029, userID:0
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2183): Preparing to send checkin request
,I/EventLogService( 2183): Accumulating logs since 1450579273128
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  910): releaseWL(438c3f88): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=684380105
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1036315826
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4771): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4771): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4771): Local Branch: 
I/Adreno-EGL( 4771): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4771): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4771):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4771): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4771): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4771): Local Branch: 
I/Adreno-EGL( 4771): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4771): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4771):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4771): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4771): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4771): Local Branch: 
I/Adreno-EGL( 4771): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4771): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4771):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4771): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4771/10029)
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 4638): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(43eb72f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4638/10154)
,D/PMS     (  910): releaseWL(43eb72f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5014/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4422cad0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/PMS     (  910): releaseWL(4422cad0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1972/10021)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4658/10027)
,D/AutoSetting( 1371): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 5014): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5014): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1371): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
,D/AutoSetting( 1371): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1371): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1371): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1371/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4741/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3620/10160)
,D/PMS     (  910): acquireWL(426f58f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1450579275765 min interval config: 0 actual interval: 1022838
D/PMS     (  910): releaseWL(426f58f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2183): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
I/iu.UploadsManager( 2183): num queued entries: 0
,I/iu.UploadsManager( 2183): num updated entries: 0
,I/iu.SyncManager( 2183): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1351): [NET] getaddrinfo-, 1
,D/libc    ( 1351): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7c31 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/PMS     (  910): acquireWL(431a2f40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
V/NativeCrypto( 2183): SSL shutdown failed: ssl=0x65aa53b0: I/O error during system call, Connection timed out
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2183): [NET] getaddrinfo-, 1
D/libc    ( 2183): [NET] getaddrinfo_proxy+
V/NativeCrypto( 2183): SSL shutdown failed: ssl=0x6e742008: I/O error during system call, Connection timed out
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =dd23 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/wpa_supplicant( 1185): nl80211: Event message available
D/wpa_supplicant( 1185): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1185): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1185): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1185): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1185): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1185): nl80211: Survey data missing
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1185): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1185): Sorted scan results
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1185): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1185): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1185): Add randomness: count=29 entropy=0
D/wpa_supplicant( 1185): Add randomness: count=30 entropy=1
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1185): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1185): reply (238) for get BSS: id=2
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1185): freq=2412
I/wpa_supplicant( 1185): level=-57
I/wpa_supplicant( 1185): tsf=0000001133781461
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG700
I/wpa_supplicant( 1185): ====
I/wpa_supplicant( 1185): id=5
I/wpa_supplicant( 1185): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1185): freq=5220
I/wpa_supplicant( 1185): level=-48
I/wpa_supplicant( 1185): tsf=0000001133781447
I/wpa_supplicant( 1185): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1185): ssid=NG7005g
I/wpa_supplicant( 1185): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 1133781461, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 1133781447, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): add 2 to mScanResults
V/ScoreHelper(  910): Only print Top 10 in ApScanList
V/ScoreHelper(  910):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
,D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (2) end of scan result ==
D/WifiManager( 1226): getScanResults enter 
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (2) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1351): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 222,
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    ( 1351): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1351): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,I/CheckinTask( 2183): Sending checkin request (12202 bytes)
,D/PMS     (  910): acquireWL(441248c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/PMS     (  910): releaseWL(431a2f40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(441248c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(441740a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1351 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1351/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1351/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(441740a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1185): environment dirty rate=16 [31][5][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2183): Checking schedule, now: 1450580299509 next: 1451103236503
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,I/CheckinService( 2183): Checking schedule, now: 1450580299537 next: 1451103236503
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,D/CheckinService( 2183): Recording last checkin time for package unspecified as 1450580299542
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,D/PMS     (  910): releaseWL(4416c808): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/GCM     ( 1351): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1185): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1185): nl80211: survey data missing!
E/wpa_supplicant( 1185): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1185): environment dirty rate=0 [0][0][0]
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3dc1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{434f3700 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1336): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): acquireWL(43cfb4f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4836 10111 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/Prism.ItemManager( 4965): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4965): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.656MB for 53840-byte allocation
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
W/AccTypeManager( 1336): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1336): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PMS     (  910): releaseWL(43cfb4f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsUpdated
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
,I/[PluginManager]RegisterService( 1371): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1371): handle notify Blinkfeed plugin client changed
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/IcingCorporaProvider( 2885): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,E/ExternalAccountType( 1336): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  910): acquireWL(426cffb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3620 10160 null
,D/PMS     (  910): releaseWL(426cffb0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): acquireWL(42a651a8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  910): Resuming delayed broadcast
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2885): UpdateCorporaTask done [took 1067 ms] updated apps [took 1067 ms] 
,I/Prism.ItemManager( 4965): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4965): loadItems() com.htc.launcher.pageview.WidgetManager@41b946e8 +
,I/Prism.WidgetManager( 4965): onLoadItems() +
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bbcd10 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  910): releaseWL(42a651a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  910): Unable to load service info ResolveInfo{4354e7c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PhoneApp( 1242): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1242): -- N1 =0
,D/PhoneApp( 1242): -- N2 =0
,D/PhoneApp( 1242): -- N3 =0
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bbcd10 -
,I/Prism.WidgetManager( 4965): onLoadItems() -
,I/Prism.ItemManager( 4965): loadItems() com.htc.launcher.pageview.WidgetManager@41b946e8 -
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(43c54c20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43c54c20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(427386e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(427386e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(425a3220): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(425a3220): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(421e74a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  910): n_update end
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  910): releaseWL(421e74a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1371): service - mHandler: update timezone
,D/AutoSetting( 1371): service - handleMessage() stop self
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1506): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1371): service - handleMessage() quit looper
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1506): service - onCreate()
,D/AutoSetting( 1371): service - onDestroy() END
,D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1506): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1506): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1506): service - mHandler: update timezone
D/DotMatrix( 1565): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1506): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1506): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1506): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41f02578 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  910): acquireWL(42539bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1175121, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42539bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{440dd6f0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(42447768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{43a06f70: PendingIntentRecord{439a99f0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450580348440, Int=0
,W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): releaseWL(42447768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4598): turnOffWifi ui setting = true
,D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4598): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4598): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4598): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4598): turnOffWifi bWifiConnected = true
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4598/1000)
D/LocationManagerService(  910): getProviders()=[gps, network]
D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  910): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4598): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4598): isCharging status = 5
,D/PMS     (  910): acquireWL(425b86e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): releaseWL(425b86e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1506): service - handleMessage() stop self
,D/AutoSetting( 1506): service - onDestroy() END
,D/AutoSetting( 1506): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4864
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4864:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4864
,D/PMS     (  910): acquireWL(41ee82d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(41ee82d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(424536f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1235122, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(424536f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(41ce3610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41ce3610): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42634780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1295122, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42634780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(423b5808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(423b5808): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425a8bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425a8bc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42485958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1355121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42485958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(423f1888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(423f1888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(41f1ba70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41f1ba70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4260ab70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1415121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4260ab70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4409b750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4409b750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43cdcef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(43cdcef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4264ec20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1475122, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4264ec20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4242d320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4242d320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42575200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42575200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425b49c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1535121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425b49c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425f6788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(425f6788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4261d0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(4261d0c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4264aed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1595121, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4264aed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4234a498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4234a498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42615c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(42615c58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424e0df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1655122, Int=0
,D/PMS     (  910): releaseWL(424e0df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(426aadd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(426aadd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(432fe2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(432fe2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
,D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42624ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1715121, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42624ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43b40358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43b40358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(426d3f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(426d3f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43b3d240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1775121, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b3d240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(441d3cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(441d3cc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(4264b8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1835122, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  910): Prepared write state in 38ms
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2015-12-19-03-02-11.bin
,D/PMS     (  910): releaseWL(4264b8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): acquireWL(426eb000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41d91b90: PendingIntentRecord{424b8e98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1723502, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{41f74710: PendingIntentRecord{425f59b0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820817, Int=1800000
V/AlarmManager(  910): sending alarm PendingIntent{42423e40: PendingIntentRecord{42740de0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1844609, Int=0
,D/HtcAppUPService( 1371): HtcUPService onCreate()
,D/HtcAppUPService( 1371): PolicyStore [Init] Get cached policy bundle
D/PMS     (  910): acquireWL(4274d880): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
V/AlarmManager(  910): sending alarm PendingIntent{4252ecf0: PendingIntentRecord{42566090 com.htc.sense.hsp startService}}, i=com.htc.upservice.action.POLICY_ALARM, t=1, cnt=1, w=1450580722546, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{4245a778: PendingIntentRecord{426b5200 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450580996498, Int=900000
,D/HtcAppUPService( 1371): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.POLICY_ALARM flg=0x4 cmp=com.htc.sense.hsp/.upservice.HtcUPService (has extras) }, this = com.htc.sense.hsp.upservice.HtcUPService@41b4c098
,D/HtcAppUPService( 1371): HtcUPServicePreference Is policy store first run: false
D/ConnectivityService(  910): Done.
V/AlarmManager(  910): sending alarm PendingIntent{43529940: PendingIntentRecord{426d1290 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450581008150, Int=1800000
D/ConnectivityService(  910): Setting timer for 720seconds
,D/HtcAppUPService( 1371): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1450581009527, default value: null
D/HtcAppUPService( 1371): HtcUPServicePreference Upload schedule enable? false
,E/GooglePlayServicesUtil( 1371): The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
,D/PMS     (  910): releaseWL(4274d880): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/HtcAppUPService( 1371): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.POLICY_ALARM
,W/ContextImpl( 4598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/HtcAppUPService( 1371): PolicyManager Cannot connect to policy server due to setting is disabled
,D/LocationManagerService(  910): getAllProviders()=[passive, gps, network]
W/BatSI   (  910): Couldn't get kernel wake lock stats
D/PMS     (  910): acquireWL(431f8150): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/HtcAppUPService( 1371): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
,D/HtcAppUPService( 1371): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
,D/HtcAppUPService( 1371): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@41b4c098
D/PMS     (  910): acquireWL(42668008): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
D/PMS     (  910): releaseWL(431f8150): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2183): Aggregate from 1450580297567 (log), 1450579208093 (data)
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023815
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024016
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025367
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028328
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029543
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): releaseWL(426eb000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  910): releaseWL(42668008): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(44257310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(44257310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(441ce130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(441ce130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(440c3480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{41d0e2e8: PendingIntentRecord{41cd91f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1895122, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(440c3480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  910): acquireWL(440a1938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(440a1938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
E/cutils-trace( 5145): Error opening trace file: No such file or directory (2)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
D/CustomizationManager( 5145): ====startRecUseTime====
D/htc.customization.log.level( 5145):  is 
W/CustomizationLogLevel( 5145): Level value is invalid, use default level 2
D/CustomizationManager( 5145):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5145): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5145): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5145): Parsing tag category name = system
I/CustomizationCIDLoader( 5145): Parsing tag category name = application
I/CustomizationCIDLoader( 5145): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5145): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5145): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5145): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5145): Parsing tag category name = Settings
D/CustomizationManager( 5145):  Read CID file spent 0.160 (s)
D/CustomizationManager( 5145):  All configurations done spent 0.160 (s)
W/HtcNativeFlag( 5145): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5145): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5145): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5145): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=5145, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  910): Copying FileAsset 0x65a93898 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  910): Skipping PackageSetting{421bde78 com.example.hello/10397} due to missing metadata
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Prism.ItemManager( 4965): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4965): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1336): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(4237dc40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
W/SQLiteConnectionPool( 2183): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/VoicemailCleanupService( 1289): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  910): releaseWL(4237dc40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1371): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1371): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1336): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
D/AccTypeManager( 1336): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/IcingCorporaProvider( 2885): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5162 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
E/ExternalAccountType( 1336): Unsupported attribute readOnly
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  910): acquireWL(43e1ad38): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2885): UpdateCorporaTask done [took 373 ms] updated apps [took 373 ms] 
W/PackageManager(  910): Unable to load service info ResolveInfo{41c308d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 5162): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5162): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5162): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5162): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5162): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5162): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5162): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5162): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5162): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5162): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5162): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5162): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5162): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5162): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5162): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5162): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5162): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5162): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5162): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5162): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5162): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5162): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5162): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5162): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5162): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5162): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5162): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5162): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5162): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5162): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5162): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5162): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5162): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5162): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5162): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5162): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5162): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5162): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5162): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5162): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5162): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5162): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5162): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5162): threadid=11: thread exiting with uncaught exception (group=0x416f9e30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5162): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5162): Process: com.google.android.apps.docs, PID: 5162
E/AndroidRuntime( 5162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5162): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5162): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5162): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5162): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5162): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 5162): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5162): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5162): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5162): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5162): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5162): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5162): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5162): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5162): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5162): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5162): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5162): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5162): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5162): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5162): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5162): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5162): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5162): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5162): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5162): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5162): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5162): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5162): Opened ClientFlag.db in read-only mode
D/Process ( 5162): killProcess, pid=5162
D/Process ( 5162): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5180 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  910): Recipient 5162
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 5162) has died.
W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 5180): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5180): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5180): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5180): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5180): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5180): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5180): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5180): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5180): threadid=10: thread exiting with uncaught exception (group=0x416f9e30)
E/AndroidRuntime( 5180): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5180): Process: com.android.keychain, PID: 5180
E/AndroidRuntime( 5180): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5180): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5180): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5180): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5180): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5180): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5180): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5180): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5180): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5180): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5194 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5180): killProcess, pid=5180
D/Process ( 5180): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450581077895.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  910): Recipient 5180
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.keychain (pid 5180) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5194): getInstance(Context context)
D/AppTag  ( 5194): getInstance(Context context)
D/AppTag  ( 5194): onCreate()
D/PMS     (  910): acquireWL(438a08b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3620 10160 null
D/PMS     (  910): releaseWL(438a08b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4143): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2183): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2183): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65350090
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66b77ab8
W/dalvikvm( 2183): threadid=48: thread exiting with uncaught exception (group=0x416f9e30)
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
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2183): killProcess, pid=2183
D/Process ( 2183): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Recipient 2183
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  910): handleWLDeath(43e1ad38): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.google.android.gms (pid 2183) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
I/ActivityManager(  910): Resuming delayed broadcast
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20997ms
E/SQLiteLog( 1351): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1351): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x64038590
W/dalvikvm( 1351): threadid=1: thread exiting with uncaught exception (group=0x416f9e30)
E/ActivityManager(  910): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1351): FATAL EXCEPTION: main
E/AndroidRuntime( 1351): Process: com.google.process.gapps, PID: 1351
E/AndroidRuntime( 1351): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1351): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1351): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1351): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1351): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1351): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1351): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1351): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1351): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1351): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1351): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1351): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1351): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1351): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1351): 	... 10 more
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop150.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5223 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1351): killProcess, pid=1351
D/Process ( 1351): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 5223): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5223 dbg=false s=true
I/DeviceManagement( 5223): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5223): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5223): WorkflowService: Starting workflow service
I/DeviceManagement( 5223): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5dda0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5223): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5223): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5223): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5223): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5237 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5223): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5223): SessionStateController: Checking invariants...
I/ActivityManager(  910): Recipient 1351
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.process.gapps (pid 1351) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20808ms
D/WifiService(  910): Client connection lost with reason: 4
I/Prism.ItemManager( 4965): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4965): loadItems() com.htc.launcher.pageview.WidgetManager@41b946e8 +
I/Prism.WidgetManager( 4965): onLoadItems() +
D/Documents( 5237): Loading roots for com.android.providers.downloads.documents
E/SQLiteDatabase( 5237): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5237): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5237): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5237): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5237): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5237): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5237): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5237): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5237): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5237): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5237): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5237): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5237): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5237): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5237): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5237): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5237): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5237): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5237): threadid=1: thread exiting with uncaught exception (group=0x416f9e30)
D/Documents( 5237): Loading roots for com.android.externalstorage.documents
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bbcd10 +
I/Prism.WidgetManager( 1273): onLoadItems() +
E/AndroidRuntime( 5237): FATAL EXCEPTION: main
E/AndroidRuntime( 5237): Process: com.android.documentsui, PID: 5237
E/AndroidRuntime( 5237): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5237): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5237): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5237): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5237): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5237): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5237): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5237): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5237): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5237): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5237): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5237): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5237): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5237): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5237): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5237): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5237): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5237): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5237): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5237): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5237): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5237): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5237): 	... 10 more
I/ActivityManager(  910): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5251 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  910): killProcessQuiet, pid=4965
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/ActivityManager(  910): App crashed! Process: com.android.documentsui
I/ActivityManager(  910): Killing 4965:com.htc.launcher:biclient/u0a76 (adj 15): empty #17
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450581078540.dbox_tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 5223): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5223): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5223): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5223): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5223): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQ,LiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5223): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  910): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5265 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  910): Recipient 4965
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 5223): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5223): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5223): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
D/Process (  910): killProcessQuiet, pid=4977
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
D/Process ( 5237): killProcess, pid=5237
D/Process ( 5237): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteDatabase( 5223): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5223): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5223): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5223): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5223): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5223): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5223): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5223): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 5223): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5dda0]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5223): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5223): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5223): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5223): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5223): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5223): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5223): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5223): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5223): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5223): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
