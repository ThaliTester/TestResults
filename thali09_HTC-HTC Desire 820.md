#### Test 565307121a686b7_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
--------- beginning of /dev/log/main
E/cutils-trace( 4546): Error opening trace file: No such file or directory (2)
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 4546): ====startRecUseTime====
D/htc.customization.log.level( 4546):  is 
W/CustomizationLogLevel( 4546): Level value is invalid, use default level 2
D/CustomizationManager( 4546):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4546): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4546): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4546): Parsing tag category name = system
I/CustomizationCIDLoader( 4546): Parsing tag category name = application
I/CustomizationCIDLoader( 4546): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4546): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4546): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4546): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4546): Parsing tag category name = Settings
D/CustomizationManager( 4546):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4546):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4546): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4546): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4546): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4546): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
D/PMS     (  910): acquireHCC(42afa118): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4546
D/PMS     (  910): acquireHCC(431c1f28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1118550144
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42026a00
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  910): acquireWL(447a2f28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4557 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4557): Binding Chromium to main looper Looper (main, tid 1) {41f3d4a0}
I/LibraryLoader( 4557): Expected native library version number "",actual native library version number ""
I/chromium( 4557): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4557): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(441e25b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428b9c20:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4557): 1106587352: getState(). Returning 12
D/PMS     (  910): acquireWL(42a06db8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): releaseWL(441e25b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4557): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4557): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4557): Local Branch: 
I/Adreno-EGL( 4557): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4557): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4557):                  aa63bbd948f41d15fc72f585e
W/chromium( 4557): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4557): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4557): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4557): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4557): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4557): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4557): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4557): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4557): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4557): CordovaWebView is running on device made by: HTC
,W/AwContents( 4557): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1271
,W/ResourceType( 4557): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4557): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41f879e8, mServedView=org.apache.cordova.engine.SystemWebView{41f4a1f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  910): Enable input method client, pid=4557
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4557): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +372ms
,D/PMS     (  910): releaseWL(447a2f28): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4557): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4557): JniHelper::setJavaVM(0x41afa010), pthread_self() = 1662799680
,I/chromium( 4557): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 11.993MB for 42652-byte allocation
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 12.070MB for 95956-byte allocation
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 12.150MB for 143930-byte allocation
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 12.264MB for 215890-byte allocation
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 12.440MB for 323830-byte allocation
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 13.690MB for 1092904-byte allocation
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 14.628MB for 1639352-byte allocation
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 15.880MB for 2459024-byte allocation
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4557): Grow heap (frag case) to 18.058MB for 3688532-byte allocation
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(42afa118): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(431c1f28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4267f550
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4267f550, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42516c98
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@4201a750
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  910): setLight #0: color=#0
,W/PMS     (  910): mWirelessDisplayManager is null
D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/jxcore-log( 4557): Initializing JXcore engine
,W/jxcore-log( 4557): JXcore engine is ready
,W/jxcore-log( 4557): Starting JXcore engine
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 313ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43eb30f8)
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
,D/NfcService( 1254): applyRouting -2
D/PMS     (  910): OOBE c monitor 11
D/PMN     (  910): wakingUp
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
D/PMS     (  910): acquireWL(42885958): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/InputMethodManagerService(  910): Disable input method client, pid=4557
I/WindowManager(  910): No lock screen! windowToken=null
,W/ResourceType( 4557): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4557): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41f4a1f0 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  910): releaseWL(42885958): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
,D/PMN     (  910): onScreenOn
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/MtpService( 1911): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting - 0
,D/MtpService( 1911): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting -2
D/PMS     (  910): acquireWL(4273f3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): acquireWL(423f4f68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  910): releaseWL(4273f3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): releaseWL(423f4f68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/AutoSetting( 1340): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
W/jxcore-log( 4557): Platform android
W/jxcore-log( 4557): 
,W/jxcore-log( 4557): Process ARCH arm
W/jxcore-log( 4557): 
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,D/AutoSetting( 1340): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19728 delay=15s
,D/TetherSettings( 4209): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4209): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4209): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4209): Cust_ConnectToPC   : spcsc>false
D/        ( 4209): Cust_ConnectToPC   : IPT>true
D/        ( 4209): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:On
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): BG scan when screen On
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): Match BG scan, scan!
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  910):    returned true
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/Settings( 4209): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
E/SmartNS_Utility( 4209): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4209): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/SmartNS_NSReceiver( 4209): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/PSReceiver( 4209): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  910): updateScreenOn: false
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4209): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4209): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4209):  defaultType:0
,I/ClockThread( 1115): stop update clock
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4613 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): acquireWL(428a1350): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(428a1350): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  910): mEventCount = 1201
,D/PMS     (  910): acquireWL(42841b78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42841b78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1742): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): onScreenOn: 1453241219665
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1742): onScreenOn: 1453241219665
W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42516c98
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42516c98, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@4201a750
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
D/PMN     (  910): goingToSleep
,D/PMS     (  910): acquireWL(42a56570): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4613 1000 null
,D/PMS     (  910): acquireWL(431f3648): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19728 mDataStallAlarmIntent=PendingIntent{428513a0: PendingIntentRecord{42877cb0 android broadcastIntent}}
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/PMS     (  910): releaseWL(42a56570): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  910): acquireWL(42852290): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
D/PMS     (  910): releaseWL(431f3648): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 4613): getMobilePolicyEnabled, result = true
,D/Process (  910): killProcessQuiet, pid=3919
,I/ActivityManager(  910): Killing 3919:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 3919
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  910): Client com.google.android.music (pid 3919): Died!
,I/jxcore-log( 4557): JXcore Cordova bridge is ready!
I/jxcore-log( 4557): 
,W/jxcore-log( 4557): JXcore engine is started
,E/jxcore  ( 4557): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4557): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4557): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/Process (  910): killProcessQuiet, pid=4341
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  910): Killing 4341:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,W/PluginManager( 4557): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  910): acquireWL(4324e728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=102695, Int=0
,I/ActivityManager(  910): Recipient 4341
,D/WifiService(  910): Client connection lost with reason: 4
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/InputMethodManagerService(  910): Disable input method client, pid=4557
W/IInputConnectionWrapper( 4557): reportFullscreenMode on inactive InputConnection
,D/PMS     (  910): releaseWL(42a06db8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:Off
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  910): updateScreenOn: false
,D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
,D/ContactMessageStore( 1239): start background delete task...
D/SmartSyncUtils( 4613): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
D/WifiService(  910): New client listening to asynchronous messages
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4201a750
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4201a750, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4201a750, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4201a750
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4289b108 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4289b108 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1340): service - mHandler: cancel location update
D/AutoSetting( 1340): service -           changes count: 0
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(434246d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(434246d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43ce43c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43ce43c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1742): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1742): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1742): onScreenOff
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4324e728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(42852290): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1183): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1183): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1183): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1183): Add randomness: count=10 en,tropy=5
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: DISCONNECTED -> INACTIVE
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  910): getDiscoveryDongleList,
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1,
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
,I/wpa_supplicant( 1183): tsf=0000000104345263
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1,
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-58
I/wpa_supplicant( 1183): tsf=0000000104345289
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
,I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-82
I/wpa_supplicant( 1183): tsf=0000000104345300
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WifiP2pService(  910): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42a798f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42a798f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42a798f8 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
,V/ScoreHelper(  910): Only print Top 10 in ApScanList
,D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 104345263, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 104345289, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 104345300, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): add 3 to mScanResults
,V/ScoreHelper(  910):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000),
D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=3894
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3894:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3894,
,D/Process (  910): killProcessQuiet, pid=3954
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3954:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3954
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=11 entropy=6
D/wpa_supplicant( 1183): Add randomness: count=12 entropy=7
D/wpa_supplicant( 1183): Add randomness: count=13 entropy=8
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=14 entropy=9
D/wpa_supplicant( 1183): Add randomness: count=15 entropy=10
D/wpa_supplicant( 1183): Add randomness: count=16 entropy=11
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,D/WifiP2pService(  910): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000121754996
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-58
I/wpa_supplicant( 1183): tsf=0000000121755022
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-84
I/wpa_supplicant( 1183): tsf=0000000121755033
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 121754996, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 121755022, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 121755033, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
V/ScoreHelper(  910): Only print Top 10 in ApScanList
,V/ScoreHelper(  910):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10,
V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
,D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(42a15660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(42a15660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(447cf720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{43575100: PendingIntentRecord{42b91d70 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121942, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{42ac2180: PendingIntentRecord{42bbfea0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=133113, Int=0
D/AutoSetting( 1340): service - handleMessage() stop self
,D/PMS     (  910): acquireWL(4464cf00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1340): service - handleMessage() quit looper
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1340): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4147
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/ActivityManager(  910): Killing 4147:com.google.android.talk/u0a111 (adj 15): empty #17
,D/PMS     (  910): acquireWL(44339d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44339d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4464cf00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/PMS     (  910): releaseWL(447cf720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43a33c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/PMS     (  910): releaseWL(43a33c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Recipient 4147
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43cace60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): acquireWL(42ddd780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(447c6130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1453241250654 tag=VacuumService
D/PMS     (  910): releaseWL(43cace60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42ddd780): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(447bec40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(447bec40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43e7ce90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(43e7ce90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(447c6130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4430e550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): acquireWL(43ba8d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4430e550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43e52c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43ba8d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(43e52c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43bf98d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(43bf98d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
D/PMS     (  910): acquireWL(43d06d80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(43d06d80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=17 entropy=12
D/wpa_supplicant( 1183): Add randomness: count=18 entropy=13
D/wpa_supplicant( 1183): Add randomness: count=19 entropy=14
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=20 entropy=15
D/wpa_supplicant( 1183): Add randomness: count=21 entropy=16
D/wpa_supplicant( 1183): Add randomness: count=22 entropy=17
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000138842061
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-58
I/wpa_supplicant( 1183): tsf=0000000138842086
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-84
I/wpa_supplicant( 1183): tsf=0000000138842097
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 138842061, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 138842086, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 138842097, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
V/ScoreHelper(  910): Only print Top 10 in ApScanList
D/WirelessDisplayService(  910): getDiscoveryDongleList
V/ScoreHelper(  910):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
,D/PMS     (  910): acquireWL(4476da10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4290dc58: PendingIntentRecord{42925f58 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141138, Int=0
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(43186aa8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(4476da10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6a90 +++++
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
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): acquireWL(4395b568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4395b568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  910): releaseWL(43186aa8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=23 entropy=18
D/wpa_supplicant( 1183): Add randomness: count=24 entropy=19
D/wpa_supplicant( 1183): Add randomness: count=25 entropy=20
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=26 entropy=21
D/wpa_supplicant( 1183): Add randomness: count=27 entropy=22
D/wpa_supplicant( 1183): Add randomness: count=28 entropy=23
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  910): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000156224820,
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-58
I/wpa_supplicant( 1183): tsf=0000000156224846
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-84
I/wpa_supplicant( 1183): tsf=0000000156224856
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiP2pService(  910): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 156224820, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 156224846, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 156224856, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): add 3 to mScanResults
D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
V/ScoreHelper(  910): Only print Top 10 in ApScanList
V/ScoreHelper(  910):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList,
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42fed2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=162695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42fed2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  910): acquireWL(42b83808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{4318e4d0: PendingIntentRecord{43b6cfd8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171456, Int=0
,D/PMS     (  910): releaseWL(42b83808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=29 entropy=24
D/wpa_supplicant( 1183): Add randomness: count=30 entropy=25
D/wpa_supplicant( 1183): Add randomness: count=31 entropy=26
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=32 entropy=27
D/wpa_supplicant( 1183): Add randomness: count=33 entropy=28
D/wpa_supplicant( 1183): Add randomness: count=34 entropy=29
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000173604737
,I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-58
I/wpa_supplicant( 1183): tsf=0000000173604763
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-84
I/wpa_supplicant( 1183): tsf=0000000173604774
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiP2pService(  910): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 173604737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 173604763, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 173604774, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
,V/ScoreHelper(  910): Only print Top 10 in ApScanList
,V/ScoreHelper(  910):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  910):  + computeScore(NG700): 1
,D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=35 entropy=30
D/wpa_supplicant( 1183): Add randomness: count=36 entropy=31
D/wpa_supplicant( 1183): Add randomness: count=37 entropy=32
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 9
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1183): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-84
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=38 entropy=33
D/wpa_supplicant( 1183): Add randomness: count=39 entropy=34
D/wpa_supplicant( 1183): Add randomness: count=40 entropy=35
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): clear disabled list - type=1
I/wpa_supplicant( 1183): No suitable network found
W/wpa_supplicant( 1183): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1183): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000173604737
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-58
I/wpa_supplicant( 1183): tsf=0000000190941856
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-84
I/wpa_supplicant( 1183): tsf=0000000173604774
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 173604737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 190941856, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2427, timestamp: 173604774, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
,V/ScoreHelper(  910): Only print Top 10 in ApScanList
,V/ScoreHelper(  910):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
,D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43f04b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43f04b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=98
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Disconnect event
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,I/wpa_supplicant( 1183): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1183): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1183): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b5cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1183): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  910):    returned true
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiPerfLock(  910): release()
,D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19729 mDataStallAlarmIntent=null
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/PMS     (  910): acquireWL(43f2c948): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
,D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
,D/WISPrService( 4209): >>>>>WISPrService start isConnected = false<<<<<
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  910):    returned true
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4209): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiService(  910): New client listening to asynchronous messages
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WISPrService( 4209): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WISPrService( 4209): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1373): Read error: ssl=0x661b5720: I/O error during system call, Connection timed out
D/libc    (  363): [NET] entry_id:4   entry:0xb792f3b0  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb792f948  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb792f2e8  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7933dc8  removed 
D/libc    (  363): [NET] entry_id:11   entry:0xb792fca0  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb792ac20  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb792ab48  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7933f70  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb792f7a8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7933cc0  removed 
D/libc    (  363): [NET] entry_id:10   entry:0xb792fae8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(42ae8728): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
,V/NativeCrypto( 1373): SSL shutdown failed: ssl=0x661b5720: I/O error during system call, Broken pipe
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
D/PMS     (  910): acquireWL(42ae3898): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(42bcef28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/PMS     (  910): releaseWL(42ae8728): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1183): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1183): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1183): Failed to initiate AP scan
I/wpa_supplicant( 1183): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  910):    returned true
,D/PMS     (  910): releaseWL(42ae3898): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  910): releaseWL(42bcef28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4658 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/PMS     (  910): acquireWL(43befdb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(43befdb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4407/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4407/10100)
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1183): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1183): Failed to initiate AP scan
,I/wpa_supplicant( 1183): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/MusicStore( 4658): Database version: 95
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4658): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4658): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4658): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4658, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4658): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,I/MediaRouter( 4658): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1911/10021)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4658/10154)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4678 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4658): getSelectedRoute
,I/NetworkMonitor( 4658): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4658/10154)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4658, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42a509e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/ACRA    ( 4678): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  910): killProcessQuiet, pid=4376
D/PMS     (  910): releaseWL(42a509e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  910): Killing 4376:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4678): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4678): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  910): acquireWL(42746c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42746c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/ActivityManager(  910): Recipient 4376
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/SystemClassLoaderAdder( 4678): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4678): Preparing secondary program dexes.
V/DexLibLoader( 4678): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4678): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4678): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4678): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4678): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4678): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4678): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4678): Dex already copied
D/OdexVerifier( 4678): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4678): Creating class loader
,V/DexLibLoader( 4678): Finished creating class loader
V/DexLibLoader( 4678): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4678): Dex already copied
D/OdexVerifier( 4678): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4678): Creating class loader
V/DexLibLoader( 4678): Finished creating class loader
V/DexLibLoader( 4678): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4678): Dex already copied
D/OdexVerifier( 4678): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4678): Creating class loader
,V/DexLibLoader( 4678): Finished creating class loader
V/DexLibLoader( 4678): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4678): Dex already copied
D/OdexVerifier( 4678): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4678): Creating class loader
V/DexLibLoader( 4678): Finished creating class loader
,V/DexLibLoader( 4678): Verifying classes from secondary dexes.
,D/DexLibLoader( 4678): DexLibLoader.ensureDexLoaded took 19 ms
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/dalvikvm( 4678): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4678): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4678): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4678): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4678): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4678): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4678): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1183): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1183): Failed to initiate AP scan
,I/wpa_supplicant( 1183): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=41 entropy=36
D/wpa_supplicant( 1183): Add randomness: count=42 entropy=37
D/wpa_supplicant( 1183): Add randomness: count=43 entropy=38
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1183):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): No APs found - clear blacklist and try again
E/wpa_supplicant( 1183): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1183): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 3
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): selected network = 1
D/wpa_supplicant( 1183): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8b5e4e8  current_ssid=0x0
D/wpa_supplicant( 1183): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): supplicant attached completed, trig,ger assoc.
D/wpa_supplicant( 1183): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1183): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1183): check if in concurrent case
I/wpa_supplicant( 1183): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1183): RSN: PMKSA cache search - network_ctx=0xb8b5e4e8 try_opportunistic=0
D/wpa_supplicant( 1183): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1183): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1183): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1183): nl80211: Unsubscribe mgmt frames handle 0xb8b5d718 (mode change)
D/wpa_supplicant( 1183): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8b5d718
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1183):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183):   * freq=2412
D/wpa_supplicant( 1183):   * Auth Type 0
D/wpa_supplicant( 1183):   * WPA Versions 0x2
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1183): nl80211: Connect request send successfully
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/,wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/wpa_supplicant( 1183): reply (376) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000202521393
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-59
I/wpa_supplicant( 1183): tsf=0000000202521413
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
,I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-82
I/wpa_supplicant( 1183): tsf=0000000202521424
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiManager( 1221): getScanResults enter 
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 202521393, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 202521413, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 202521424, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Connect event
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1183): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1183): Add randomness: count=44 entropy=39
I/wpa_supplicant( 1183): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on association
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1183): EAPOL: enable timer tick
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, tru,e
I/wpa_supplicant( 1183): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): Get randomness: len=32 entropy=40
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8b5d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
W/dalvikvm( 4678): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef2b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1183):    broadcast key
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1183): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1183): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1183): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1183): set send_ind_to_ndc = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1183): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1183): EAPOL authentication completed successfully
I/wpa_supplicant( 1183): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WISPrService( 4209): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WISPrService( 4209): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
W/dalvikvm( 4678): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  910):    returned true
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(428d71e8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 1
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1183): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:3
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a573b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a573b8 target=com.android.internal.util.StateMachine$SmHandler }
,E/FbInjectorInitializer( 4678): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4678): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4678): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4678): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=4407
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4407:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4407
,D/AutoSetting( 1340): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4708 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
,D/AutoSetting( 1340): Util - no network available!
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
D/AutoSetting( 1340): service - onCreate()
,D/AutoSetting( 1340): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1340): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  910): request 4287cf48 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1340): service - mHandler: cancel location update
,D/AutoSetting( 1340): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4678): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4678): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4678): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4708): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4708): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4708): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4708): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4724 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4708/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4708/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4708/10079)
,D/Process (  910): killProcessQuiet, pid=4431
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4738 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  910): Killing 4431:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4431
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 9.954MB for 84664-byte allocation
E/dalvikvm( 4678): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4678): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4678): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4678): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4678): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4678): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4678): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4678): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4678): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4678): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4678): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4678): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4678): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4678): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4678): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4678): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4678): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4678): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4738): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 10.014MB for 39954-byte allocation
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 10.090MB for 79892-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4738/10151)
,V/WebViewChromiumFactoryProvider( 4738): Binding Chromium to main looper Looper (main, tid 1) {41f43390}
,I/LibraryLoader( 4738): Expected native library version number "",actual native library version number ""
,I/chromium( 4738): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4738): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(42af63c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  910): acquireWL(43225088): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  910): releaseWL(42af63c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 4738): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4738): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4738): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4738): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4738): Local Branch: 
I/Adreno-EGL( 4738): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4738): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4738):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4678): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/NSApplication( 4738): Starting up...
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c017f0 u0 ReceiverList{42c016d0 4678 com.facebook.katana/10027/u0 remote:42a9e750}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c017f0 u0 ReceiverList{42c016d0 4678 com.facebook.katana/10027/u0 remote:42a9e750}}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4738/10151)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4322c168 u0 ReceiverList{4322c108 4678 com.facebook.katana/10027/u0 remote:423f4a20}}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4738/10151)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
,D/Process (  910): killProcessQuiet, pid=4448
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4448:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
I/ActivityManager(  910): Recipient 4448
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2188): num queued entries: 0
I/iu.UploadsManager( 2188): num updated entries: 0
,I/iu.SyncManager( 2188): NEXT; no task
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  910): getAllNetworkInfo called by com.test.thalitest (4557/10389)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/PMS     (  910): acquireWL(43b7ccd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43b7ccd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1183): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1183): EAPOL: disable timer tick
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4678): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4678): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4678): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  910): releaseWL(428d71e8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1183): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  910): WAN detection
,D/WISPrService( 4209): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/MDST    (  910): default: setTeardownRequested(true)
,D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1183): Change stage from stage0 to stage3
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@428c4010
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
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
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(447bb168): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4708/10079)
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/PMS     (  910): acquireWL(43ce40f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1453241172985 min interval config: 0 actual interval: 149437
D/PMS     (  910): acquireWL(4299cb60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43ce40f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2188): Checking schedule, now: 1453241322427 next: 1453241202951
,I/CheckinService( 2188): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2188, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2188): Preparing to send checkin request
,I/EventLogService( 2188): Accumulating logs since 1453241168293
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  910): releaseWL(447bb168): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4812 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4812): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4812): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4812): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4812): install
,I/MultiDex( 4812): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4812): loading existing secondary dex files
,I/MultiDex( 4812): load found 3 secondary dex files
,I/MultiDex( 4812): install done
,W/dalvikvm( 4812): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4812): VFY: unable to resolve instance field 36
,W/dalvikvm( 4812): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4812): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4812): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4812): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4812): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4812): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4812): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4812): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4812): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4812): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/LocationInitializer( 2188): Restart initialization of location
,E/MDM     ( 1221): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,D/PMS     (  910): acquireWL(435bd6f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  910): releaseWL(435bd6f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
D/AuthorizationBluetoothService( 1373): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1373): Proximity feature is not enabled.
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4812): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1929179692
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  910): releaseWL(43f2c948): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  910): Found interface wlan0
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  910): acquireWL(429f4c40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(429f4c40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4708/10079)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
,D/AccTypeManager( 1324): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4658/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 4658): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(442b0ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/PMS     (  910): acquireWL(437a2630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,W/AccTypeManager( 1324): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1324): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1183): Change stage from stage3 to stage1
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(442b0ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1911/10021)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1324): Unsupported attribute readOnly
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(437a2630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1340): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/MobileConnectivityChangeReceiver( 4708): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4708): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1340): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1340): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4738/10151)
,D/AutoSetting( 1340): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1340): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(42f46ca0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1453241172985 min interval config: 0 actual interval: 150550
D/PMS     (  910): releaseWL(42f46ca0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4188): Grow heap (frag case) to 13.517MB for 1821008-byte allocation
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 2188): num queued entries: 0
,I/iu.UploadsManager( 2188): num updated entries: 0
,I/iu.SyncManager( 2188): NEXT; no task
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getAllNetworkInfo called by com.test.thalitest (4557/10389)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/PMS     (  910): acquireWL(42a583d0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1373): [NET] getaddrinfo-,err=8
D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1373): [NET] getaddrinfo-, 1
D/libc    ( 1373): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4ae3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 191
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1373): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,W/fb4a(:<default>):UserScope( 4678): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4678): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1373): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WVCdm   (  371): PrepareKeyRequest: nonce=8221843
,D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1373): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(446d9190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  910): acquireWL(43d31980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(446d9190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43225088): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(43d01660): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/PMS     (  910): releaseWL(42a583d0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4678): Called registerBroadcastReceiver twice.
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1373/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(43d01660): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42956f78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1373/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1373/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(42956f78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(428a9ab8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4658 10154 null
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4658): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4658): Conditions not met for autocaching.
,I/MusicLeanback( 4658): Stop autocaching.
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4658, uid=10154, userID:0
D/PMS     (  910): releaseWL(428a9ab8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,I/Adreno-EGL( 4812): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4812): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4812): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4812): Local Branch: 
I/Adreno-EGL( 4812): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4812): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4812):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,W/Settings( 4812): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4812): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4812): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4812): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4812): Local Branch: 
I/Adreno-EGL( 4812): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4812): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4812):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4812): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4812): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4812): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4812): Local Branch: 
I/Adreno-EGL( 4812): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4812): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4812):                  aa63bbd948f41d15fc72f585e
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 12644 seconds from now (1453241324155)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4812/10029)
D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/CheckinRequestBuilder( 2188): Classify the device as Phone.
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2188): [NET] getaddrinfo-, 1
,D/libc    ( 2188): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6727 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 18
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2188): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2188): Sending checkin request (12084 bytes)
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=7 [13][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d39b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [10][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,I/CheckinRequestBuilder( 2188): Classify the device as Phone.
,I/CheckinTask( 2188): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2188): Checking schedule, now: 1453241324879 next: 1453764261874
,I/CheckinService( 2188): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,I/CheckinService( 2188): Checking schedule, now: 1453241324901 next: 1453764261874
,I/CheckinService( 2188): active receiver: disabled
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,D/CheckinService( 2188): Recording last checkin time for package unspecified as 1453241324907
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/PMS     (  910): releaseWL(43d31980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4299cb60): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(44740da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(44740da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44344330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  910): releaseWL(44344330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1f1b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4738): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  910): killProcessQuiet, pid=4393
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4393:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4393
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1324): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4879 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsUpdated
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1324): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1324): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,E/ExternalAccountType( 1324): Unsupported attribute readOnly
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4879): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4879): MmsConfig.loadMmsSettings
,W/dalvikvm( 4879): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4879): VFY: unable to resolve instance field 36
,W/dalvikvm( 4879): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4879): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4902 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4879, uid=10111, userID:0
,W/Settings( 4879): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4879, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4879, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4879, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4879, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4879, uid=10111, userID:0
,D/MessageFrequencyProvider( 4902): onCreate
D/PMS     (  910): acquireWL(42af65f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4879 10111 null
,D/MmsCustomizationProvider( 4902): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4902): GetPrviateResource
,V/GetPrviateResource( 4902): GetPrviateResource
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
D/MmsCustomizationProvider( 4902): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1340): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1340): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Resuming delayed broadcast
,I/Babel   ( 4879): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4879): MmsConfig.loadFromDatabase
,I/IcingCorporaProvider( 2884): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,E/Babel   ( 4879): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4879): MmsConfig.loadFromResources
,E/Babel   ( 4879): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4879): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  910): acquireWL(43ccb3b8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42af65f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  910): killProcessQuiet, pid=4483
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4483:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4483
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ProviderInstaller( 4879): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4902): sense_version=6.0
,D/BTAccessoryUtil( 4902): createReceiver
,D/BTAccessoryUtil( 4902): registerReceiver return intent = null
D/MessageCustFlag( 4902): sku_id=99
,W/SystemReader( 4902): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4902): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4902): networkCode: 
,D/MessageCustFlag( 4902): sku_id=99
D/MmsConfig( 4902): SIE smsPri: null
,D/MmsConfig( 4902): networkCode: 
,W/PackageManager(  910): Unable to load service info ResolveInfo{43b65aa8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/HtcTelephonyCapability( 4902): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4902): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4902): getRATByHtcTelephonyCapability:1
W/SystemReader( 4902): Cannot find qct_8960_interface, use default value instead
D/PMS     (  910): releaseWL(43ccb3b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
D/PMS     (  910): acquireWL(42a4db78): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42a4db78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43efe790): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/dalvikvm-heap( 4188): Grow heap (frag case) to 15.219MB for 1821008-byte allocation
D/PMS     (  910): acquireWL(43478aa8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4188 10160 null
,D/PMS     (  910): releaseWL(43efe790): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4188): Grow heap (frag case) to 16.950MB for 1821008-byte allocation
D/PMS     (  910): acquireWL(43f74eb0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43478aa8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(43f74eb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  910): acquireWL(42a52af8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42a52af8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43eb1b48): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): releaseWL(43eb1b48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  910): acquireWL(43beb148): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43beb148): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2188): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  910): acquireWL(42af9308): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2188): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/IcingCorporaProvider( 2884): UpdateCorporaTask done [took 377 ms] updated apps [took 377 ms] 
,I/ActivityManager(  910): Resuming delayed broadcast
I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(447c51e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(447c51e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
,D/PMS     (  910): acquireWL(44340a20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44340a20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43a1e678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43a1e678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4430e6f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4430e6f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41fcecb0 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/Icing   ( 2188): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2188): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(42af9308): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41fcecb0 -
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,D/Messaging( 4902): mNeedToUpdateDate2 start
,D/MmsConfig( 4902): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4902): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4902): 
D/MmsAsyncWorkHandler( 4902): HM tk = 20001
,D/ReportIndicatorCache( 4902): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4902): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41f446f8
,I/Messaging( 4902): mccmnc> 
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/DraftCache( 4902): [DraftCache/1] DraftCache.constructor
D/DraftCache( 4902): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4902): networkCode: 
,D/Messaging( 4902): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4902): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4902): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4902): createReceiver
,D/MessageCustFlag( 4902): sense_version=6.0
,D/Jerry   ( 4902): start to preload cursor >>>>>>>
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/Messaging( 4902): mNeedToUpdateDate2: false
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
V/MmsProvider( 1239): Update uri=content://mms, match=0
,V/MmsProvider( 1239): selection=st=129 AND m_type!=134
,D/Messaging( 4902): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4902): TransactionService is going to be woken up.
D/Messaging( 4902): ViewCache CreatePreload
,D/Messaging( 4902): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4902): 1-Creating TransactionService
,D/Cust_MMSMS( 4902): _has_set_default_values_2=true
V/TransactionService( 4902): onStartCommand: 1
,D/MmsSystemEventReceiver( 4902): unRegisterForConnectionStateChanges
V/TransactionService( 4902): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4902): Loading previous transactions.
,D/MsgPreferenceUtils( 4902): def_index: 0
,D/MsgPreferenceUtils( 4902): globalIndex = 1
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MsgPreferenceUtils( 4902): phone state: true
D/AccFlag ( 1239): device_type: 1
D/MsgPreferenceUtils( 4902): sd state: false
,D/MsgPreferenceUtils( 4902): vIndex = 0
D/TransactionService( 4902): Force set service start id to 1
V/TransactionService( 4902): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4902): unRegisterForConnectionStateChanges
D/TransactionService( 4902): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4902): Destroying TransactionService
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/TransactionService( 4902): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1239): sku_id=99
,D/DraftCache( 4902): [DraftCache/484] rebuildCache
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4902): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/Jerry   ( 1239): URI_DRAFT
,D/DraftCache( 4902): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4902): [DraftCache/484] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4902): 
D/MmsAsyncWorkHandler( 4902): HM tk = 20002
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1239): sku_id=99
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1239): sku_id=99
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43a18ce8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4879): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(447aea30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=222695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(447aea30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44783ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=99
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(44783ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/AutoSetting( 1340): service - mHandler: update timezone
,D/AutoSetting( 1340): service - handleMessage() stop self
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1340): service - handleMessage() quit looper
,D/AutoSetting( 1340): service - onDestroy() END
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1497): service - mHandler: update timezone
,D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,V/NotificationService(  910): batLight: plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c80000
D/qdlights(  910): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{42317810 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 6 2 11
,D/Process (  910): killProcessQuiet, pid=4498
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4498:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4498
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  910): acquireWL(43b5c878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43b5c878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43cb5340 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4114
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4114:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4114
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(43ae9380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=282695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43ae9380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43a4a7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43a4a7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=99
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4397ae78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4397ae78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(431c26f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=342695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(431c26f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(4292f220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/PMS     (  910): releaseWL(4292f220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(427ec378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=402695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(427ec378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(425f16f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425f16f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1560): [EventService] reorderNotification, total:0
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/HeadsetPhoneState( 1631): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0,
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,D/TetherSettings( 4209): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4209): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4209): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4209): Cust_ConnectToPC   : spcsc>false
D/        ( 4209): Cust_ConnectToPC   : IPT>true
,D/        ( 4209): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4209): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4209): Index of the first 1 = -1
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4209): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4209): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4209): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4209): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4209): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(428177b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(428177b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42cb1330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=462695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42cb1330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(42986860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42986860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(428b2900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  910): releaseWL(428b2900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(43b55ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=522696, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b55ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42ab6b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42ab6b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(429bebb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429bebb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(427d6388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=582695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(427d6388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42907700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(42907700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(429ce8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(429ce8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1239): sku_id=99
,D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/Process (  910): killProcessQuiet, pid=4529
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4529:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4529
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(431c23c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=642695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(431c23c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(428b93a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(428b93a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43138c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43138c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42a3e0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=702696, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42a3e0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(429af2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(429af2b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42846598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=762695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42846598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43a05498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43a05498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42a23058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=822695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42a23058): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4285d108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4285d108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43d0bea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=882695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43d0bea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42bc06f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bc06f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42961170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=942695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42961170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4275b740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4275b740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(429c6830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1002695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(429c6830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): acquireWL(4205c508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{421ad3b8: PendingIntentRecord{428ce7c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782165, Int=0
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,I/ActivityManager(  910): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4981 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  910): sending alarm PendingIntent{436db308: PendingIntentRecord{431b02e0 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4992 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{427d0888: PendingIntentRecord{42a14ba8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453241327970, Int=10800000
,V/AlarmManager(  910): sending alarm PendingIntent{42f1fe20: PendingIntentRecord{42b87480 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453241880987, Int=1800000
,V/AlarmManager(  910): sending alarm PendingIntent{42045000: PendingIntentRecord{42044fa8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453242048325, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{446694b0: PendingIntentRecord{4220ecb0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453242120321, Int=0
,D/PMS     (  910): acquireWL(42a26088): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): acquireWL(43b986f0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42a26088): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4613): call getInstance()
,D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4613): MY_DEBUG = false
,D/PMS     (  910): acquireWL(42bc1258): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4613 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4613): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4613): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,I/EventLogService( 2188): Aggregate from 1453241322460 (log), 1453240080936 (data)
,D/PMS     (  910): releaseWL(4205c508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4613): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4613): SettingOnTime = 1453269600000, randomSettingOnTime = 1453266696000
D/SmartSyncScreenOnOffTimeReceiver( 4613): SettingOffTime = 1453255200000, randomSettingOffTime = 1453259011000
D/SmartSyncScreenOnOffTimeReceiver( 4613): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4613): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4613): bNightModeTurnOffOnce = false,
W/BatSI   (  910): Couldn't get kernel wake lock stats
I/ImageRamCache( 4981): create image Cache, size: 31457280.
I/ImageRamCache( 4981): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4981): create image Cache, size: 12582912.
,I/FeedSettings( 4981): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
D/PMS     (  910): releaseWL(42bc1258): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4992/10049)
I/FeedSettings( 4981): GroupBudget 0.500000 0.380000
I/FeedSettings( 4981): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4981): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4981): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4981): loadGridSize() with Alternative
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(43b986f0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4981): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4981): [NET] getaddrinfo-,err=8
D/libc    ( 4981): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4981): [NET] getaddrinfo-, 1
D/libc    ( 4981): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4d27 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/Process (  910): killProcessQuiet, pid=4708
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4708:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4708
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=206
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4981): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.launcher (4981/10076)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.launcher (4981/10076)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/Process (  910): killProcessQuiet, pid=4724
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4724:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4724
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(4294eb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4294eb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42acdf80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1062695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42acdf80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Disconnect event
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1183): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1183): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b5cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1183): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,D/Tethering(  910): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  910):    returned true
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
,D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19730 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
,D/WISPrService( 4209): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  910): acquireWL(43bc5e78): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
,D/MDST    (  910): default: setEnableApn apnType =default , enable=true
,D/WISPrService( 4209): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WISPrService( 4209): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 4209): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1373): Read error: ssl=0x63ef5b48: I/O error during system call, Connection timed out
D/libc    (  363): [NET] entry_id:5   entry:0xb792af60  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb792f410  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb792f108  removed 
V/NativeCrypto( 1373): SSL shutdown failed: ssl=0x63ef5b48: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:4   entry:0xb792efd8  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb792f2e0  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(446a8cd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(43b77818): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1373/10029)
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0",
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1183): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0,
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =2
,I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available,
D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  910): releaseWL(446a8cd8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,D/PMS     (  910): releaseWL(43b77818): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4478bbe8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(4478bbe8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4658/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4658): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1911/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/AutoSetting( 1340): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5023 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
,D/AutoSetting( 1340): Util - no network available!
,D/AutoSetting( 1340): service - onCreate()
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
D/AutoSetting( 1340): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1340): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  910): request 4287cf48 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1340): service - mHandler: cancel location update
,D/AutoSetting( 1340): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 5023): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5023): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5023): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5023): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5038 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5023/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5023/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5023/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4738/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
I/iu.UploadsManager( 2188): num queued entries: 0
I/iu.UploadsManager( 2188): num updated entries: 0
,I/iu.SyncManager( 2188): NEXT; no task
,D/Process (  910): killProcessQuiet, pid=4557
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
I/ActivityManager(  910): Killing 4557:com.test.thalitest/u0a389 (adj 15): empty #17
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4557
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
D/wpa_supplicant( 1183): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=45 entropy=8
D/wpa_supplicant( 1183): Add randomness: count=46 entropy=9
D/wpa_supplicant( 1183): Add randomness: count=47 entropy=10
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1183):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1183): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1183): No APs found - clear blacklist and try again
E/wpa_supplicant( 1183): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1183): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 3
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 0
I/wpa_supplicant( 1183): wpa_s->is_screen_on 0
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): selected network = 1
D/wpa_supplicant( 1183): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8b5e4e8  current_ssid=0x0
D/wpa_su,pplicant( 1183): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1183): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1183): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1183): check if in concurrent case
I/wpa_supplicant( 1183): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1183): RSN: PMKSA cache search - network_ctx=0xb8b5e4e8 try_opportunistic=0
D/wpa_supplicant( 1183): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1183): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1183): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1183): nl80211: Unsubscribe mgmt frames handle 0xb8b5d718 (mode change)
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1183): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8b5d718
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb8b5d718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1183):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183):   * freq=2412
D/wpa_supplicant( 1183):   * Auth Type 0
D/wpa_supplicant( 1183):   * WPA Versions 0x2
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1183): nl80211: Connect request send successfully
,D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1183): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (376) for get BSS: id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-58
I/wpa_supplicant( 1183): tsf=0000001070551750
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-46
I/wpa_supplicant( 1183): tsf=0000000202521393
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=4
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-82
I/wpa_supplicant( 1183): tsf=0000001070551760
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 1070551750, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 202521393, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 1070551760, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1221): getScanResults enter 
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
,D/wpa_supplicant( 1183): nl80211: Connect event
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1183): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Add randomness: count=48 entropy=11
I/wpa_supplicant( 1183): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on association
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1183): EAPOL: enable timer tick
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
,I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): Get randomness: len=32 entropy=12
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8b5d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef2b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    broadcast key
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1183): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1183): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1183): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
E/wpa_supplicant( 1183): wlan0: Connect to SSID: NG700
,D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1183): set send_ind_to_ndc = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
D/Tethering(  910): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1183): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1183): EAPOL authentication completed successfully
I/wpa_supplicant( 1183): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...,
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WISPrService( 4209): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4209): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  910):    returned true
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 1
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
,D/PMS     (  910): acquireWL(43b685a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1183): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a573b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a573b8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
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
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1,
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16,
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true,
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0,
D/PMS     (  910): releaseWL(43b685a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -86 abnormalRssiCnt = 0 newLinkSpeed = 1
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 1,
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97,
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
,D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 0,
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true,
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState,
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -86, Link speed: 1, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  910): WAN detection
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 4209): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_1 (gone) T]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS,
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@428c4010
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  910): acquireWL(426cc250): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:2
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1183): Change stage from stage0 to stage3
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5023/10079)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(426cc250): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): acquireWL(429afad8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  910): acquireWL(434697b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1453241324907 min interval config: 0 actual interval: 863909
D/PMS     (  910): releaseWL(429afad8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2188): Checking schedule, now: 1453242188825 next: 1453241354874
,I/CheckinService( 2188): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2188, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2188): Preparing to send checkin request
,I/EventLogService( 2188): Accumulating logs since 1453242120434
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/wpa_supplicant( 1183): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1183): EAPOL: disable timer tick
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3342181657
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2266492893
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  910): releaseWL(43bc5e78): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  910): NoActiveNetworkState
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42b077e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4658/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (5023/10079)
,V/Tethering(  910): bSetPropertyMultiRAB:false
,I/NetworkMonitor( 4658): type=WIFI subType= reason=null isConnected=true
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1221/10029),
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(447bb190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/PMS     (  910): releaseWL(447bb190): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(42b077e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4812): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4812): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4812): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4812): Local Branch: 
I/Adreno-EGL( 4812): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4812): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4812):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1911/10021)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4678/10027)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1340): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/MobileConnectivityChangeReceiver( 5023): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5023): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4738/10151)
D/AutoSetting( 1340): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1340): service - onStartCommand() screen is off, don't request location
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1340): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1340): service - onStartCommand() check timezone in 30000
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1340/10055)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4188/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1453241324907 min interval config: 0 actual interval: 865006
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  910): acquireWL(4287ec80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4287ec80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,W/Settings( 4812): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2188): num queued entries: 0
,I/iu.UploadsManager( 2188): num updated entries: 0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/iu.SyncManager( 2188): NEXT; no task
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4812): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4812): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4812): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4812): Local Branch: 
I/Adreno-EGL( 4812): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4812): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4812):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/ActivityManager(  910): Start proc com.test.thalitest for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener: pid=5099 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/PMS     (  910): acquireWL(42a4c878): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1373): [NET] getaddrinfo-,err=8
D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1373): [NET] getaddrinfo-, 1
D/libc    ( 1373): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ad82 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,I/Adreno-EGL( 4812): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4812): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4812): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4812): Local Branch: 
I/Adreno-EGL( 4812): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4812): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4812):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4812/10029)
,D/ConnectivityService(  910): getAllNetworkInfo called by com.test.thalitest (5099/10389)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1373): [NET] getaddrinfo_proxy-, success
,I/CheckinRequestBuilder( 2188): Classify the device as Phone.
D/jxcore_app_log( 5099): JniHelper::setJavaVM(0x41afa010), pthread_self() = 1074172312
,E/JX-Cordova( 5099): JXcore wasn't initialized yet
,D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1373): [NET] getaddrinfo-,err=8
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2188): [NET] getaddrinfo-,err=8
,V/NativeCrypto( 2188): SSL shutdown failed: ssl=0x6e836d70: I/O error during system call, Connection timed out
,V/NativeCrypto( 2188): SSL shutdown failed: ssl=0x6cf01ba8: I/O error during system call, Connection timed out
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2188): [NET] getaddrinfo-, 1
D/libc    ( 2188): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =73cb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    ( 1373): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4,
,D/libc    ( 1373): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 68
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2188): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/PMS     (  910): acquireWL(4347cba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/PMS     (  910): releaseWL(42a4c878): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1373/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(4347cba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a9d6c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1373/10029)
,I/CheckinTask( 2188): Sending checkin request (12210 bytes)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1373/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
D/PMS     (  910): releaseWL(42a9d6c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=25 [32][8][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2188): Classify the device as Phone.
,I/CheckinTask( 2188): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2188): Checking schedule, now: 1453242190966 next: 1453765127948
,I/CheckinService( 2188): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671,
,I/CheckinService( 2188): Checking schedule, now: 1453242191007 next: 1453765127948
,I/CheckinService( 2188): active receiver: disabled
,D/CheckinService( 2188): Recording last checkin time for package unspecified as 1453242191013
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023660
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023891
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023894
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023897
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025544
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025559
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028407
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029671
,D/PMS     (  910): releaseWL(434697b0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/Process (  910): killProcessQuiet, pid=4879
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4879:com.google.android.talk/u0a111 (adj 15): empty #17
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  910): Recipient 4879
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43f4e1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43f4e1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024,
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c8bb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =,
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175,
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!,
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1324): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5126 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1324): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1324): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsUpdated
I/Prism.ItemManager( 4981): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4981): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1324): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 5126): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5126): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 4902): query uri: content://htc-mms-customization/mms-ua/ua_string
,W/dalvikvm( 5126): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 5126): VFY: unable to resolve instance field 36
,W/dalvikvm( 5126): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/MmsCustomizationProvider( 4902): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 5126): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 5126): MmsConfig.loadFromDatabase
,V/JNIHelp ( 5126): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Babel   ( 5126): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5126): MmsConfig.loadFromResources
,E/Babel   ( 5126): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5126): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5126, uid=10111, userID:0
,W/Settings( 5126): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=5126, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=5126, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=5126, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5126, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5126, uid=10111, userID:0
,D/PMS     (  910): acquireWL(435bfa28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5126 10111 null
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1340): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1340): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Resuming delayed broadcast
,I/IcingCorporaProvider( 2884): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  910): acquireWL(43f17978): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43f17978): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(435bfa28): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43eed240): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 5126): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,W/PackageManager(  910): Unable to load service info ResolveInfo{43ccf760 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  910): releaseWL(43eed240): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(44327720): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42ac57b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4188 10160 null
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): releaseWL(42ac57b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(44327720): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42b65c88): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  910): releaseWL(42b65c88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43c185f0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): releaseWL(43c185f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43d2ee28): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2188): Null package name or gms related package.  Ignoreing.
D/PMS     (  910): releaseWL(43d2ee28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43c12c78): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2188): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/IcingCorporaProvider( 2884): UpdateCorporaTask done [took 418 ms] updated apps [took 418 ms] 
I/ActivityManager(  910): Resuming delayed broadcast
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(43897730): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43897730): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(42b9cf58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42b9cf58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43f55a98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43f55a98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41fcecb0 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/Prism.ItemManager( 4981): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4981): loadItems() com.htc.launcher.pageview.WidgetManager@41fa7968 +
,I/Prism.WidgetManager( 4981): onLoadItems() +
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41fcecb0 -
,I/Icing   ( 2188): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2188): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/Prism.WidgetManager( 4981): onLoadItems() -
,I/Prism.ItemManager( 4981): loadItems() com.htc.launcher.pageview.WidgetManager@41fa7968 -
,D/PMS     (  910): releaseWL(43c12c78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44d903b0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 5126): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4981
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4981:com.htc.launcher:biclient/u0a76 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4981
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43c515b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43c515b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1340): service - mHandler: update timezone
,D/AutoSetting( 1340): service - handleMessage() stop self
,D/AutoSetting( 1340): service - handleMessage() quit looper
,D/AutoSetting( 1340): service - onDestroy() END
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1497): service - mHandler: update timezone
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f9cab8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 3 11 5 11
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43897c00 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(442d8a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1122695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(442d8a20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4992
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4992:com.htc.aurora/u0a49 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4992
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(43f10c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43f10c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43f10998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43f10998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43efec38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1182695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43efec38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43ef90c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43ef90c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(43ee2dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1242695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43ee2dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43ec5b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43ec5b50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  910): acquireWL(43ebf940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4246d210: PendingIntentRecord{4246d190 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1302695, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43ebf940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 5173): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5173): ====startRecUseTime====
D/htc.customization.log.level( 5173):  is 
W/CustomizationLogLevel( 5173): Level value is invalid, use default level 2
D/CustomizationManager( 5173):  Read ACC file spent 0.068 (s)
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5173): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5173): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5173): Parsing tag category name = system
I/CustomizationCIDLoader( 5173): Parsing tag category name = application
I/CustomizationCIDLoader( 5173): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5173): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5173): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5173): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5173): Parsing tag category name = Settings
D/CustomizationManager( 5173):  Read CID file spent 0.115 (s)
D/CustomizationManager( 5173):  All configurations done spent 0.116 (s)
W/HtcNativeFlag( 5173): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5173): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5173): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5173): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=5173, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  910): killProcessQuiet, pid=5099
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  910): Killing 5099:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  910): Skipping PackageSetting{42620ed8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1324): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): acquireWL(437d3b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(437d3b98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
W/SQLiteConnectionPool( 2188): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1340): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/[PluginManager]RegisterService( 1340): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1324): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1324): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/IcingCorporaProvider( 2884): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5188 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1324): Unsupported attribute readOnly
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  910): acquireWL(4400fdb0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4400fdb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43eb6ef0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2884): UpdateCorporaTask done [took 432 ms] updated apps [took 432 ms] 
E/SQLiteDatabase( 5188): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5188): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5188): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5188): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5188): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5188): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5188): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5188): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5188): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5188): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5188): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5188): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5188): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5188): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5188): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5188): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5188): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5188): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5188): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5188): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5188): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5188): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5188): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5188): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5188): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5188): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5188): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5188): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5188): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5188): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5188): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5188): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5188): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5188): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5188): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5188): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5188): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5188): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5188): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5188): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5188): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5188): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5188): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5188): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5188): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5188): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5188): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5188): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5188): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5188): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5188): threadid=11: thread exiting with uncaught exception (group=0x41b0be30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5188): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5188): Process: com.google.android.apps.docs, PID: 5188
E/AndroidRuntime( 5188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5188): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5188): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5188): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5188): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5188): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 5188): killProcess, pid=5188
D/Process ( 5188): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5206 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  910): Recipient 5188
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 5188) has died.
W/ContextImpl( 5206): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5219 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5206): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5206): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5206): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5206): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5206): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5206): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5206): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5206): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5206): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5206): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5206): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5206): threadid=10: thread exiting with uncaught exception (group=0x41b0be30)
E/AndroidRuntime( 5206): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5206): Process: com.android.keychain, PID: 5206
E/AndroidRuntime( 5206): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5206): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5206): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5206): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5206): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5206): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5206): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5206): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5206): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5206): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 5219): getInstance(Context context)
D/Process ( 5206): killProcess, pid=5206
D/Process ( 5206): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453242429404.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  910): Recipient 5206
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.keychain (pid 5206) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5219): getInstance(Context context)
D/AppTag  ( 5219): onCreate()
D/PMS     (  910): acquireWL(42875270): PARTIAL_WAKE_LOCK  AsyncService 0x1 4188 10160 null
W/dalvikvm( 4226): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PMS     (  910): releaseWL(42875270): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2188): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2188): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2188): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2188): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2188): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e8883b8
I/LocationSettingsChecker( 2188): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2188): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2188): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6cf23460
W/dalvikvm( 2188): threadid=48: thread exiting with uncaught exception (group=0x41b0be30)
E/DriveAsyncService( 2188): disk I/O error (code 3850)
E/DriveAsyncService( 2188): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2188): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2188): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2188): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2188): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2188): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2188): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2188): Process: com.google.android.gms, PID: 2188
E/AndroidRuntime( 2188): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2188): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2188): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2188): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2188): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2188): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2188): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2188): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2188): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2188): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2188): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2188): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2188): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms
D/Process ( 2188): killProcess, pid=2188
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
E/SQLiteDatabase( 2188): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2188): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2188): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2188): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2188): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2188): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2188): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2188): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2188): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/SQLiteOpenHelper( 2188): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2188): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2188): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2188): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2188): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2188): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2188): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2188): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41fcecb0 +
I/Prism.WidgetManager( 1271): onLoadItems() +
I/ActivityManager(  910): Recipient 2188
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.gms (pid 2188) has died.
D/PMS     (  910): handleWLDeath(43eb6ef0): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  910): Client connection lost with reason: 4
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30997ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30997ms
I/ActivityManager(  910): Resuming delayed broadcast
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30987ms
E/SQLiteLog( 1373): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1373): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fcd728
W/dalvikvm( 1373): threadid=1: thread exiting with uncaught exception (group=0x41b0be30)
E/AndroidRuntime( 1373): FATAL EXCEPTION: main
E/AndroidRuntime( 1373): Process: com.google.process.gapps, PID: 1373
E/AndroidRuntime( 1373): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1373): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1373): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1373): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1373): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1373): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1373): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1373): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1373): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1373): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1373): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1373): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1373): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1373): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1373): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1373): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1373): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1373): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1373): 	... 10 more
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
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5249 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1373): killProcess, pid=1373
D/Process ( 1373): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 5249): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5249 dbg=false s=true
I/DeviceManagement( 5249): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5249): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5249): WorkflowService: Starting workflow service
I/DeviceManagement( 5249): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41f68df8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5249): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5249): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5249): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5249): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5263 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5249): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5249): SessionStateController: Checking invariants...
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Recipient 1373
I/ActivityManager(  910): Process com.google.process.gapps (pid 1373) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30722ms

```
