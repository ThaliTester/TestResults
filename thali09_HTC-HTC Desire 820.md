#### Test 56151093c886730_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  915):    returned true
E/cutils-trace( 4473): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4473): ====startRecUseTime====
D/htc.customization.log.level( 4473):  is 
W/CustomizationLogLevel( 4473): Level value is invalid, use default level 2
D/CustomizationManager( 4473):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4473): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4473): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4473): Parsing tag category name = system
I/CustomizationCIDLoader( 4473): Parsing tag category name = application
I/CustomizationCIDLoader( 4473): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4473): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4473): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4473): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4473): Parsing tag category name = Settings
D/CustomizationManager( 4473):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4473):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4473): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4473): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4473): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4473): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  915): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  915): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  915): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  915): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  915): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4473
D/PMS     (  915): acquireHCC(425db6f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 915 1000 null
D/PMS     (  915): acquireHCC(4315e690): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 915 1000 null
W/asset   (  915): Copying FileAsset 0x6c6786c0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  915): @test_code: getHtcIntentFlag: 0 obj: 1144201616
D/PMS     (  915): acquireWL(43733c30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 915 1000 null
I/FeedHostManager( 1277): [onPause]
I/FeedProviderManager( 1277): onPause
I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c23820
I/SocialFeedProvider( 1277): +onPause
I/SocialFeedProvider( 1277): -onPause
I/ActivityManager(  915): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4484 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1277): [trimMemory] 20
W/asset   ( 4484): Copying FileAsset 0x5c825428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4484): Binding Chromium to main looper Looper (main, tid 1) {41ad7678}
I/LibraryLoader( 4484): Expected native library version number "",actual native library version number ""
I/chromium( 4484): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4484): Initializing chromium process, renderers=0
D/PMS     (  915): acquireWL(4372ca78): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  915): java.lang.Throwable: stack dump
D/BluetoothManagerService(  915): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  915): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423ee9f0:true
W/System.err(  915): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  915): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  915): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  915): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  915): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4484): 1101978720: getState(). Returning 12
I/Adreno-EGL( 4484): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4484): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4484): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4484): Local Branch: 
I/Adreno-EGL( 4484): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4484): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4484):                  aa63bbd948f41d15fc72f585e
W/chromium( 4484): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4484): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4484): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4484): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4484): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4484): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4484): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4484): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4484): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4484): CordovaWebView is running on device made by: HTC
,D/PMS     (  915): acquireWL(43730878): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  915): releaseWL(4372ca78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/AwContents( 4484): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  915): Disable input method client, pid=1277
,W/ResourceType( 4484): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4484): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b1f310, mServedView=org.apache.cordova.engine.SystemWebView{41ae4f78 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  915): Enable input method client, pid=4484
W/AwContents( 4484): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  915): Displayed com.test.thalitest/.MainActivity: +307ms
,D/PMS     (  915): releaseWL(43733c30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4484): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4484): JniHelper::setJavaVM(0x415af048), pthread_self() = 1663763384
,D/JX-Cordova( 4484): jxcore cordova android initializing
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 12.001MB for 42652-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 12.098MB for 95956-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 12.179MB for 143930-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 12.293MB for 215890-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 12.466MB for 323830-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 12.727MB for 485740-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 13.727MB for 1092904-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 14.640MB for 1639352-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 15.942MB for 2459024-byte allocation
,W/CpuWake (  915): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  915): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  915): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  915): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  915): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  915): <<release mCpuPerf_Freq wakelock
,D/PMS     (  915): releaseHCC(425db6f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  915): releaseHCC(4315e690): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 18.075MB for 3688532-byte allocation
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1189): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
,D/WIFI_ICON( 1121): WifiActivity: 0
,D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/jxcore-log( 4484): Initializing JXcore engine
,W/jxcore-log( 4484): JXcore engine is ready
,W/jxcore-log( 4484): Starting JXcore engine
,W/jxcore-log( 4484): Platform android
W/jxcore-log( 4484): 
,W/jxcore-log( 4484): Process ARCH arm
W/jxcore-log( 4484): 
,I/PMS     (  915): Going to sleep due to screen timeout...
,I/SensorManager(  915): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421ca9b0
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  915): disable: get sensor name = CM36282 Light sensor
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 2
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421ca9b0, eanble = 0, strlen(mName) = 59
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  915): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c74e28
W/SensorService(  915): Listener[1] = com.htc.smartdim.sensor_eye@41bafb58
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  915): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  915): Couldn't get kernel wake lock stats
V/LightsService(  915): setLight #2: color=#0
D/qdlights(  915): set_light_buttons_func: on=0 brightness=0
V/LightsService(  915): setLight #0: color=#0
,W/PMS     (  915): mWirelessDisplayManager is null
D/WirelessDisplayService(  915): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  915): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/PMS     (  915): releaseWL(43730878): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/SurfaceControl(  915): Excessive delay in blankDisplay() while turning screen off: 329ms
D/PMS     (  915): nativeSetInteractive:false
D/PMS     (  915): nativeSetInteractive:false done
D/PMS     (  915): nativeSetAutoSuspend:true
D/PMS     (  915): nativeSetAutoSuspend:true done
D/HABCtrl (  915): TPE algorithm. remove timeout.
D/PMS     (  915): OOBE c monitor 11
I/InputManager(  915): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  915): screenObserver, isScreenOn=false
D/NfcService( 1258): ScreenObserver: OFF
D/NfcService( 1258): applyRouting - 0
D/NfcService( 1258): applyRouting -2
I/IntentController( 1121): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  915): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@41ead538)
I/InputMethodManagerService(  915): Disable input method client, pid=4484
D/PMS     (  915): acquireWL(43de1c68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  915): releaseWL(43de1c68): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  915): wakingUp
,V/KeyguardServiceDelegate(  915): **** SHOWN CALLED ****
D/WirelessDisplayService(  915): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  915): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  915): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  915): No lock screen! windowToken=null
D/PMN     (  915): onScreenOn
D/PMS     (  915): acquireWL(4255c460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4255c460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/MtpService( 1954): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1954): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): applyRouting -2
,D/AutoSetting( 1331): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  915): acquireWL(42466030): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  915): releaseWL(42466030): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/TetherSettings( 3836): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3836): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3836): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3836): Cust_ConnectToPC   : spcsc>false
D/        ( 3836): Cust_ConnectToPC   : IPT>true
D/        ( 3836): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3836): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3836): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3836): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3836): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/PowerUI ( 1121): closing low battery warning: level=98
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  915): ACTION_SCREEN_ON
I/AlarmManager(  915): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  915): [AlarmQueuing] done recovering
I/AlarmManager(  915): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  915): [AlarmQueuing] done EPS screen off alarm recovering
D/AutoSetting( 1331): service - onCreate()
D/WirelessDisplayService(  915): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  915): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  915): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/PSReceiver( 3836): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1331): service - AddressCache: using context: com.htc.Weather
V/NotificationService(  915): batLight: plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c80000
D/qdlights(  915): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/WifiDataStallTracker(  915): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  915): startDataStallAlarm: tag=20945 delay=15s
,I/ClockThread( 1121): stop update clock
I/SmartNS_PSService( 3836): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3836): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3836):  defaultType:0
,D/AutoSetting( 1331): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
D/WifiNative-wlan0(  915): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/LocationManagerService(  915): request 42412b00 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  915): provider request: passive ProviderRequest[ON interval=0]
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  915): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1189): SET_SCREEN_ON:On
I/wpa_supplicant( 1189): htc_wext_set_keepalive +
I/wpa_supplicant( 1189): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1189): getPrivFuncNum +	
I/wpa_supplicant( 1189): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1189): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1189): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
D/WifiStateMachine(  915): [ScoreAP] + current TXpacket:140, mTXpacketCount:140, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  915): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  915): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  915): batLight: plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c80000
D/qdlights(  915): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/BatteryController( 1121): status:2 level:98 unsupport:false plugged:true
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  915): updateScreenOn: false
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  915): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4537 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/jxcore-log( 4484): JXcore Cordova bridge is ready!
I/jxcore-log( 4484): 
,W/jxcore-log( 4484): JXcore engine is started
,I/chromium( 4484): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourceType( 4484): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4484): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ae4f78 VFEDH.C. .F....ID 0,0-720,1134 #64}
,W/ContextImpl( 4537): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  915): acquireWL(42604bc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  915): releaseWL(42604bc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4537): isEpsOn(), nState = 0
D/PMS     (  915): acquireWL(42580510): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42580510): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOn: 1453034316308
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOn: 1453034316308
D/PMS     (  915): acquireWL(4240a768): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4537 1000 null
,I/SensorManager(  915): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c74e28
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 2,
W/SensorService(  915): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c74e28, eanble = 0, strlen(mName) = 91
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  915): Listener[0] = com.htc.smartdim.sensor_eye@41bafb58
,W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  915): goingToSleep
D/PMS     (  915): acquireWL(4372a758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 915 1000 null
,D/PMS     (  915): releaseWL(4240a768): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  915): ACTION_SCREEN_OFF
I/AlarmManager(  915): [AlarmQueuing] screen off now: 
I/AlarmManager(  915): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  915): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  915): stopDataStallAlarm: current tag=20945 mDataStallAlarmIntent=PendingIntent{42586eb8: PendingIntentRecord{42591968 android broadcastIntent}}
I/AlarmManager(  915): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  915): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1189): SET_SCREEN_ON:Off
D/WifiNative-wlan0(  915): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1189): htc_wext_set_keepalive +
I/wpa_supplicant( 1189): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1189): getPrivFuncNum +	
I/wpa_supplicant( 1189): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1189): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1189): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1189): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1189): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  915):    returned true
,D/SmartSyncUtils( 4537): getMobilePolicyEnabled, result = true
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
D/PMS     (  915): acquireWL(425c3738): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 915 1000 null
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  915): updateScreenOn: false
D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
D/ContactMessageStore( 1245): Background delete complete
I/jxcore-log( 4484): Toggling radios to true
I/jxcore-log( 4484): 
,D/BluetoothAdapter( 4484): enable(): BT is already enabled..!
,D/SmartSyncUtils( 4537): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4537): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4537): isEpsOn(), nState = 0
,W/ContextImpl( 4537): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiManager( 4484): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  915):    returned true
W/HtcDLNAServiceManager(  915): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  915): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  915): Settings:Agentvalue: 2
W/Settings:Agent(  915): >> traceCallingStack()
W/Settings:Agent(  915): Process.myPid(): 915
W/Settings:Agent(  915): Process.myTid(): 1376
W/Settings:Agent(  915): Process.myUid(): 1000
W/Settings:Agent(  915): 
W/Settings:Agent(  915): 
W/System.err(  915): java.lang.Throwable: stack dump
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
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,D/WifiManager( 4484): disconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiManager( 4484): reconnect: Base Package Name=com.test.thalitest, uid=10389
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,I/jxcore-log( 4484): Radios toggled
I/jxcore-log( 4484): 
D/WifiService(  915): setWifiEnabled: true pid=4484, uid=10389
E/WifiService(  915): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  915): isSprintWifiRestricted(): false
I/WifiService(  915): isMdmWifiRestricted(): false
D/WifiSettingsStore(  915): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiService(  915): New client listening to asynchronous messages
D/WifiService(  915): New client listening to asynchronous messages
D/PMS     (  915): releaseWL(425c3738): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/jxcore-log( 4484): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4484): 
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doBoolean: DISCONNECT
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): TDLS: Tear down peers
,I/wpa_supplicant( 1189): wpa_driver_nl80211_disconnect(reason_code=3)
,D/PMS     (  915): acquireWL(426c0da8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(426c0da8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1567): [EventService] getTotalRam: 1873 Mb
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1189): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1189): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1189): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  915): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  915): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  915): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  915): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1189): TDLS: Remove peers on disassociation
D/HTCRequest(  915): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  915): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1189): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/PMS     (  915): acquireWL(438d67f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1189): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1189): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1189): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb76abbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1189):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1189): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1189): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1189): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1189): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1189): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1189): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1189): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1189): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
D/Tethering(  915): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1189): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1189): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1189): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1189): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1189): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1189): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1189): nl80211: Event message available
D/wpa_supplicant( 1189): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1189): nl80211: Ignore disco,nnect event triggered during reassociation
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  915):    returned true
D/WifiPerfLock(  915): release()
D/WifiStateMachine(  915): PerfLock released for exiting ConnectedState
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
D/Tethering(  915): interfaceStatusChanged wlan0, false
D/Tethering(  915): [isWifi] getHotspotEnabled: false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm: null
D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOff
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1189): Power_Mode_Type mode = 0
I/wpa_supplicant( 1189): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 61
D/PMS     (  915): releaseWL(438d67f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  915): acquireWL(42568dd0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 915 1000 null
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  915): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41bafb58
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 1
W/SensorService(  915): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41bafb58, eanble = 0, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  915): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  915): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  915): pid=915, uid=1000
W/SensorService(  915): Active sensors: size = 0
W/SensorService(  915): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41bafb58, eanble = 0, strlen(mName) = 36
W/SensorService(  915): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  915): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  915):    returned true
I/SensorManager(  915): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41bafb58
D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  915): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/ActivityThread(  915): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41f8ed20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  915): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41f8ed20 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  915): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  915): doBoolean: RECONNECT
D/DhcpStateMachine(  915): [RunningState] Stop DHCP
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): Fast associate: Old scan results
I/wpa_supplicant( 1189): wpa_supplicant_scan enter
I/wpa_supplicant( 1189): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1189): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1189): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  915):    returned true
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1189): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1189): nl80211: Event message available
D/WifiStateMachine(  915): Enter handleNetworkDisconnect
D/wpa_supplicant( 1189): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  915): stopDataStallAlarm: current tag=20946 mDataStallAlarmIntent=null
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
I/wpa_supplicant( 1189): Power_Mode_Type mode = 0
I/wpa_supplicant( 1189): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/AutoSetting( 1331): service - mHandler: cancel location update
D/WifiNative-wlan0(  915):    returned true
D/AutoSetting( 1331): service -           changes count: 0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  915): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  915): Provision feature enable=false
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  915): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  915): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/UsbnetStateTracker(  915): isAvailable+-
D/UsbnetStateTracker(  915): reconnect
D/UsbnetStateTracker(  915): isAvailable+-
D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiStateMachine(  915): Exit handleNetworkDisconnect
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  915): doBoolean: SET pno 1
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): CTRL_IFACE SET 'pno'='1'
I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3836): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  915): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  915): default: reconnect()
D/MDST    (  915): default: setTeardownRequested(false)
D/MDST    (  915): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  915): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  915): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  915): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  915): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  915): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  915): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3836): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3836): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3836): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  915): New client listening to asynchronous messages
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1189): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1189): nl80211: Event message available
D/wpa_supplicant( 1189): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1189): nl80211: Event message available
D/wpa_supplicant( 1189): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1189): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1189): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1189): nl80211: Survey data missing
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
D/WifiNative-wlan0(  915):    returned true
D/wpa_supplicant( 1189): Sorted scan results
I/wpa_supplicant( 1189): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
D/wpa_supplicant( 1189): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1189): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1189): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1189): wpa_supplicant_pick_network+
I/wpa_supplicant( 1189): Selecting BSS from priority group 1
I/wpa_supplicant( 1189): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1189): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1189): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1189):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1189):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1189): Start print parameters
I/wpa_supplicant( 1189): wpa_s->wpa_state is 3
I/wpa_supplicant( 1189): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1189): isConcurrentMode() is 0
I/wpa_supplicant( 1189): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1189): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1189): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1189): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1189): wpa_s->reassociate is 1
I/wpa_supplicant( 1189): wpa_s->is_screen_on 0
I/wpa_supplicant( 1189): wpa_s->ifname wlan0
I/wpa_supplicant( 1189): End print parameters
I/wpa_supplicant( 1189): selected network = 1
D/wpa_supplicant( 1189): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb76ad4e8  current_ssid=0x0
D/wpa_supplicant( 1189): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1189): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1189): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1189): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1189): check if in concurrent case
I/wpa_supplicant( 1189): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  915): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  915): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/wpa_supplicant( 1189): wpa_supplicant_associate, 1777
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1189): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1189): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1189): RSN: PMKSA cache search - network_ctx=0xb76ad4e8 try_opportunistic=0
D/WifiNative-wlan0(  915): doString: LIST_DONGLES
D/wpa_supplicant( 1189): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1189): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1189): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1189): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1189): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1189): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1189): nl80211: Unsubscribe mgmt frames handle 0xb76ac718 (mode change)
D/wpa_supplicant( 1189): nl80211: Subscribe to mgmt frames with non-AP handle 0xb76ac718
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Register frame type=0xd0 nl_handle=0xb76ac718
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1189): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1189):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1189):   * freq=2412
D/wpa_supplicant( 1189):   * Auth Type 0
D/wpa_supplicant( 1189):   * WPA Versions 0x2
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1189): nl80211: Connect request send successfully
D/wpa_supplicant( 1189): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  915): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
V/NativeCrypto( 1359): Read error: ssl=0x660db298: I/O error during system call, Connection timed out
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1189): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1189): reply (238) for get BSS: id=0
I/wpa_supplicant( 1189): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1189): freq=5220
I/wpa_supplicant( 1189): level=-47
I/wpa_supplicant( 1189): tsf=0000000022990133
I/wpa_supplicant( 1189): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1189): ssid=NG7005g
I/wpa_supplicant( 1189): ====
I/wpa_supplicant( 1189): id=1
I/wpa_supplicant( 1189): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1189): freq=2412
I/wpa_supplicant( 1189): level=-51
I/wpa_supplicant( 1189): tsf=0000000106794922
I/wpa_supplicant( 1189): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1189): ssid=NG700
I/wpa_supplicant( 1189): ####
W/ConnectivityService(  915): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  915): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  915): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  915): handleConnectivityChange: resetting
D/ConnectivityService(  915): resetConnections(wlan0, 3)
W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  915): getDiscoveryDongleList
D/WifiStateMachine(  915): == begin of scan result ==
D/WifiStateMachine(  915): == (2) end of scan result ==
D/libc    (  364): [NET] entry_id:3   entry:0xb8152320  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8151fd8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8152428  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb8152240  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb81520e8  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb814df60  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/WifiManager( 1225): getScanResults enter 
V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x660db298: I/O error during system call, Broken pipe
D/WirelessDisplayService(  915): getDiscoveryDongleList
D/WifiStateMachine(  915): == begin of scan result ==
D/WifiStateMachine(  915): == (2) end of scan result ==
D/WifiStateMachine(  915): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 22990133, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/WifiStateMachine(  915): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 106794922, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  915): add 2 to mScanResults
D/ConnectivityService(  915): flush DNS cache for net 1(wlan0)
D/WifiNotificationController(  915): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/PMS     (  915): acquireWL(4436adf8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  915): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  915): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  915): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  915): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  915): startScan Pid: 915 Uid 1000
D/WifiNative-wlan0(  915): doBoolean: SET pno 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/QuickSettingWifi( 1121): receive.wifiConnect:false wifiAPname:null elapse:1
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1189): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1189): nl80211: Event message available
D/wpa_supplicant( 1189): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: SCAN
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1189): wpa_supplicant_scan enter
I/wpa_supplicant( 1189): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1189): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1189): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1189): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1189): wpa_supplicant_trigger_scan -
D/WifiNative-wlan0(  915):    returned true
W/wpa_supplicant( 1189): Failed to initiate AP scan
I/wpa_supplicant( 1189): Failed to initiate AP scan, Failed_to_scan_counter:1
D/PMS     (  915): acquireWL(42639780): PARTIAL_WAKE_LOCK  NetworkStats 0x1 915 1000 null
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
D/ConnectivityService(  915): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
D/ConnectivityService(  915): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
D/BatSI   (  915): WIFI scan started for: 450a0300 uid:1000
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/QuickSettingWifi( 1121): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  915): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  915): releaseWL(4436adf8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(42639780): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  915): mActiveDefaultNetwork: -1
D/ConnectivityService(  915): handleInetConditionChange: no active default network - ignore
,D/wpa_supplicant( 1189): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1189): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1189): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1189): Wireless event: cmd=0x8b15 len=20
D/Tethering(  915): interfaceLinkStateChanged wlan0, false
D/Tethering(  915): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1189): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1189): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1189): nl80211: if_removed already cleared - ignore event
,D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1189): nl80211: Event message available
D/wpa_supplicant( 1189): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1189): nl80211: Connect event
D/wpa_supplicant( 1189): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1189): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1189): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1189): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1189): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1189): Add randomness: count=6 entropy=1
I/wpa_supplicant( 1189): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1189): TDLS: Remove peers on association
D/wpa_supplicant( 1189): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1189): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1189): EAPOL: enable timer tick
D/wpa_supplicant( 1189): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1189): htc_wext_set_keepalive +
I/wpa_supplicant( 1189): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1189): getPrivFuncNum +	
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1189): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1189): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1189): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1189): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/Tethering(  915): interfaceLinkStateChanged wlan0, true
D/wpa_supplicant( 1189): Get randomness: len=32 entropy=2
D/Tethering(  915): interfaceStatusChanged wlan0, true
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED,
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  915): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  915): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  915): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  915): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  915): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  915): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  915): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  915): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  915): Enter handleAssociatedWithEvent
D/WifiStateMachine(  915): Associated
,D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  915): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  915): Exit handleAssociatedWithEvent
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  915): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  915): updateConnectedAP...
D/WifiApDatabaseHandler(  915): updateConnectedAP...
D/WifiStateMachine(  915): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  915): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  915): This record is existed, only update it...
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  915): updateConnectedAP...
I/wpa_supplicant( 1189): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb76ac9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1189):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 10
,D/wpa_supplicant( 1189): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1189): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1189): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f08b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1189):    broadcast key
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1189): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,E/wpa_supplicant( 1189): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1189): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1189): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1189): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1189): wlan0: Connect to SSID: NG700
,D/wpa_supplicant( 1189): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1189): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  915): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1189): set send_ind_to_ndc = 0
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1189): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1189): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1189): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1189): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1189): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1189): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1189): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1189): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1189): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1189): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 1189): EAPOL authentication completed successfully
I/wpa_supplicant( 1189): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1189): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1189): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1189): nl80211: if_removed already cleared - ignore event
D/Tethering(  915): interfaceLinkStateChanged wlan0, true
D/Tethering(  915): interfaceStatusChanged wlan0, true
,D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  915): [isWifi] getHotspotEnabled: false
D/HTCRequest(  915): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  915): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  915): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  915): updateConnectedAP...,
,D/WifiStateMachine(  915): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  915): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  915): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  915): This record is existed, only update it...
D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  915): updateConnectedAP...,
,I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  915): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  915): Provision feature enable=false
D/ConnectivityService(  915): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  915): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  915): updateConnectedAP...
,D/WISPrService( 3836): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3836): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  915): doBoolean: SET pno 0
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  915):    returned true
,D/DhcpStateMachine(  915): [StoppedState] Start DHCP
,D/WifiStateMachine(  915): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER SETSUSPENDMODE 0
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1189): Power_Mode_Type mode = 1
I/wpa_supplicant( 1189): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  915):    returned true
D/WifiNative-wlan0(  915): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1,
D/WifiNative-wlan0(  915):    returned null
D/wpa_supplicant( 1189): nl80211: Event message available
E/WifiStateMachine(  915): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  915): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 1189): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1189): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP",
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  915):    returned null
,D/WifiStateMachine(  915): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  915): acquireWL(438d8bc8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 915 1000 null
D/WifiStateMachine(  915): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  915): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425de6f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425de6f8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1121): receive.wifiConnect:false wifiAPname:null elapse:1
,W/ActivityManager(  915): Activity pause timeout for ActivityRecord{42554038 u0 com.test.thalitest/.MainActivity t2}
,V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  915): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  915): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4578 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
D/GpsLocationProvider(  915): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  915): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/GpsLocationProvider(  915): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
V/Tethering(  915): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  915): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  915): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  915): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
D/CaptivePortalTracker(  915): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  915): NoActiveNetworkState
I/Tethering(  915): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  915): ipv4Default null
D/PMS     (  915): acquireWL(4250bb28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 915 1000 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/PMS     (  915): releaseWL(4250bb28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/Tethering(  915): No IPv4 upstream interface, giving up.
,D/Tethering(  915): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.htc.launcher (1277/10076)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.docs (4333/10100)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/ConnectivityHelper( 1277): [onReceive] WIFI(1): CONNECTING
D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.docs (4333/10100)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,I/MusicStore( 4578): Database version: 95
,W/ContextImpl( 4578): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/wpa_supplicant( 1189): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1189): EAPOL: disable timer tick
,W/ContextImpl( 4578): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4578): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4578): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4578): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4578, uid=10154, userID:0
,D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
,D/MediaRouterService(  915): Client com.google.android.music (pid 4578): Registered
,I/MediaRouter( 4578): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  915): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  915):     Client/Owner: Client
D/WifiDisplayAdapter(  915):     GroupId: 
D/WifiDisplayAdapter(  915):     Passphrase: 
D/WifiDisplayAdapter(  915):     SessionId: 0
D/WifiDisplayAdapter(  915):     IP Address: }
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.music (4578/10154)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1954/10021)
,I/ActivityManager(  915): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4598 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4578): getSelectedRoute
,I/NetworkMonitor( 4578): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.google.android.music (4578/10154)
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4578, uid=10154, userID:0
,D/ACRA    ( 4598): ACRA is enabled for com.facebook.katana, intializing...
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/Process (  915): killProcessQuiet, pid=4267
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ACRA    ( 4598): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4598): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  915): Killing 4267:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMS     (  915): acquireWL(42afc828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/PMS     (  915): releaseWL(42afc828): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/SystemClassLoaderAdder( 4598): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4598): Preparing secondary program dexes.
V/DexLibLoader( 4598): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4598): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4598): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4598): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4598): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4598): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock,
,V/DexLibLoader( 4598): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4598): Dex already copied
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.,
V/DexLibLoader( 4598): Creating class loader
V/DexLibLoader( 4598): Finished creating class loader
V/DexLibLoader( 4598): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar,
V/DexLibLoader( 4598): Dex already copied
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.,
V/DexLibLoader( 4598): Creating class loader
V/DexLibLoader( 4598): Finished creating class loader,
V/DexLibLoader( 4598): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4598): Dex already copied
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.,
V/DexLibLoader( 4598): Creating class loader
V/DexLibLoader( 4598): Finished creating class loader
V/DexLibLoader( 4598): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4598): Dex already copied,
D/OdexVerifier( 4598): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4598): Creating class loader
V/DexLibLoader( 4598): Finished creating class loader
V/DexLibLoader( 4598): Verifying classes from secondary dexes.
,D/DexLibLoader( 4598): DexLibLoader.ensureDexLoaded took 16 ms,
,I/ActivityManager(  915): Recipient 4267
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  915): Client connection lost with reason: 4
,W/dalvikvm( 4598): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4598): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  915): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  915): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  915):    returned true
,D/WifiNative-wlan0(  915): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1189): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1189): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  915):    returned true
,D/WifiNative-wlan0(  915): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1189): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  915):    returned true
,D/WifiStateMachine(  915): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  915): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  915): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  915): releaseWL(438d8bc8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  915): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  915): doBoolean: SignalStrength 97
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1189): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  915):    returned true
D/WifiStateMachine(  915): gateway: /192.168.1.1
,D/WifiNative-wlan0(  915): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1189): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1189): htc_wext_set_keepalive +
I/wpa_supplicant( 1189): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1189): getPrivFuncNum +	
I/wpa_supplicant( 1189): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1189): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1189): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1189): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1189): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  915):    returned true
D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  915): VerifyingLinkState enter
D/WifiStateMachine(  915): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  915): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  915): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  915): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1121): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiDataStallTracker(  915): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  915): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1121): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  915): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  915): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  915): WAN detection
D/ConnectivityService(  915): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  915): Provision feature enable=false
D/ConnectivityService(  915): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  915): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  915): default: teardown()
D/MDST    (  915): default: setTeardownRequested(true)
D/MDST    (  915): default: setEnableApn apnType =default , enable=false
D/MDST    (  915): default: setTeardownRequested(true)
D/ConnectivityService(  915): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  915): Unexpected mtu value: android.net.wifi.WifiStateTracker@424632a8
,D/ConnectivityService(  915): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3836): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  915): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  915): syncGetConfiguredNetworks
D/WIFI_ICON( 1121): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1121): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  915): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  915): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  915): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  915): handleConnectivityChange: resetting
D/Nat464Xlat(  915): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  915): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  915): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  915): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  915): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  915): acquireWL(43660e58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 915 1000 null
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  915): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  915):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [1][0][0]
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
I/logwrapper(  364): /system/bin/ip terminated by exit(254)
I/QuickSettingWifi( 1121): receive.wifiConnect:true wifiAPname:NG700 elapse:1
W/dalvikvm( 4598): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  915): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/PMS     (  915): releaseWL(43660e58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/dalvikvm( 4598): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4598): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4598): Verify
,D/WifiService(  915): New client listening to asynchronous messages
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4598): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4598): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  915): killProcessQuiet, pid=3876
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  915): Killing 3876:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 3876
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1331): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  915): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4649 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1331): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1331): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
,D/AutoSetting( 1331): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1331): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4598): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4649): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4649): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4649): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  915): killProcessQuiet, pid=4170
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  915): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4663 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  915): Killing 4170:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4649/10079)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4649/10079)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4649/10079)
D/PMS     (  915): acquireWL(42aae1e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(429ea708): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1453034266985 min interval config: 0 actual interval: 52450
D/PMS     (  915): releaseWL(42aae1e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2183): Checking schedule, now: 1453034319444 next: 1453034296960
,I/CheckinService( 2183): active receiver: enabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2183, uid=10029, userID:0
,I/CheckinService( 2183): Preparing to send checkin request
,I/EventLogService( 2183): Accumulating logs since 1453034263548
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,I/ActivityManager(  915): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4678 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  915): Killing 4303:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  915): killProcessQuiet, pid=4303
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  915): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 4303
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 9.961MB for 84664-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4678): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4678): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  915): Recipient 4170
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4678): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 9.977MB for 28144-byte allocation
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4598): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,W/ContextImpl( 4678): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4598): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4598): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4598): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4598): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4598): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4598): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/ContextImpl( 4678): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/dalvikvm( 4598): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4598): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4598): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4598): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4598): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4598): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4598): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/jxcore-log( 4484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4484): 
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.045MB for 39954-byte allocation
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.122MB for 79892-byte allocation
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4678/10151)
,V/WebViewChromiumFactoryProvider( 4678): Binding Chromium to main looper Looper (main, tid 1) {41ade1c0}
,I/LibraryLoader( 4678): Expected native library version number "",actual native library version number ""
,I/chromium( 4678): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4678): Initializing chromium process, renderers=0
,D/PMS     (  915): acquireWL(43b26540): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  915): acquireWL(437a3348): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  915): releaseWL(437a3348): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/AudioManagerAndroid( 4678): BLUETOOTH permission is missing!
I/ActivityManager(  915): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4700 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/Adreno-EGL( 4678): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4678): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4678): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4678): Local Branch: 
I/Adreno-EGL( 4678): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4678): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4678):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4700): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4700): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4700): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4700): install
,I/MultiDex( 4700): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/NSApplication( 4678): Starting up...
,I/dalvikvm-heap( 4598): Grow heap (frag case) to 10.284MB for 75760-byte allocation
,I/MultiDex( 4700): loading existing secondary dex files
,I/MultiDex( 4700): load found 3 secondary dex files
,I/MultiDex( 4700): install done
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4678/10151)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4678/10151)
D/PMS     (  915): releaseWL(42568dd0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  915): NetTransition Wakelock for ConnectedState released by timeout
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42969330 u0 ReceiverList{42212de8 4598 com.facebook.katana/10027/u0 remote:42963160}}
,D/Process (  915): killProcessQuiet, pid=4333
W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42969330 u0 ReceiverList{42212de8 4598 com.facebook.katana/10027/u0 remote:42963160}}
W/BroadcastQueue(  915): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426b48d8 u0 ReceiverList{420c8bc8 4598 com.facebook.katana/10027/u0 remote:426003f8}}
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
I/ActivityManager(  915): Killing 4333:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  915): mTetherableUsbRegexs:{(usb0)(ncm0)}
,W/dalvikvm( 4700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4700): VFY: unable to resolve instance field 36
D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  915): [AlarmQueuing] connectivity wifi: true
,W/dalvikvm( 4700): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/GpsLocationProvider(  915): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  915): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  915): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  915): ignore wifi update if we are not in OPENING or CLOSING
,V/JNIHelp ( 4700): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/Tethering(  915): bSetPropertyMultiRAB:false
,D/Tethering(  915): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4578): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  915): Recipient 4333
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by  (915/1000)
D/PMS     (  915): acquireWL(4221fca0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 915 1000 null
D/PMS     (  915): releaseWL(4221fca0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.google.android.music (4578/10154)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.musicenhancer (3951/10053)
I/Tethering(  915): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  915): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  915): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  915): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  915): Found interface wlan0
,D/Tethering(  915): TetherMasterSM: InitialState processMessage what=3
I/ConnectivityHelper( 1277): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  915): NoActiveNetworkState
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.setupwizard (4649/10079)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  915): getNetworkInfo networkType=1 called by com.htc.launcher (1277/10076)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  915): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.backuptransport (1577/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/PMS     (  915): acquireWL(41cd6968): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/PMS     (  915): releaseWL(41cd6968): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1954/10021)
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/PMS     (  915): acquireWL(43a7e900): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43a7e900): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1331): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ProviderInstaller( 4700): Installed default security provider GmsCore_OpenSSL
,D/MobileConnectivityChangeReceiver( 4649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4649): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
,D/AutoSetting( 1331): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1331): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1331): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1331): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.magazines (4678/10151)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.sense.hsp (1331/10055)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4700): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.apps.plus (4076/10160)
W/dalvikvm( 4700): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4700): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4700): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4700): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4700): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4700): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/CheckinService( 2183): Checkin interval check for package: unspecified last checkin: 1453034266985 min interval config: 0 actual interval: 52979
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  915): acquireWL(43003140): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43003140): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/dalvikvm-heap( 4076): Grow heap (frag case) to 13.509MB for 1821008-byte allocation
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,D/NativeLibraryUtils( 4700): Install completed successfully. count=14 extracted=0
,E/MDM     ( 1225): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2183): Restart initialization of location
D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
,D/WVCdm   (  371): PrepareKeyRequest: nonce=4269988524
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  915): acquireWL(431636a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(431636a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/jxcore-log( 4484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4484): 
,I/jxcore-log( 4484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4484): 
,I/jxcore-log( 4484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4484): 
,I/jxcore-log( 4484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4484): 
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (4700/10029)
I/jxcore-log( 4484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4484): 
W/Settings( 4700): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 4484): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4484): 
,I/Adreno-EGL( 4700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4700): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4700): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4700): Local Branch: 
I/Adreno-EGL( 4700): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4700): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4700):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4484): Test app app.js loaded
I/jxcore-log( 4484): 
,D/PMS     (  915): releaseWL(4372a758): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,I/chromium( 4484): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1535845493
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4700): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4700): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4700): Local Branch: 
I/Adreno-EGL( 4700): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4700): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4700):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4700): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4700): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4700): Local Branch: 
I/Adreno-EGL( 4700): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4700): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4700):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2183): [NET] getaddrinfo-,err=8
D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2183): [NET] getaddrinfo-, 1
D/libc    ( 2183): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8cc9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2183): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,D/libc    ( 2183): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2183): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2183): Sending checkin request (12197 bytes)
,D/WifiStateMachine(  915): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  915): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  915): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  915): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-,err=8
D/libc    (  915): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  915): [NET] getaddrinfo-, 1
,D/libc    (  915): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =38f1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/CheckinRequestBuilder( 2183): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  915): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2183): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  915): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  915): Find DNS Address www.htc.com/104.81.130.175
,D/ConnectivityService(  915): getNetworkInfo networkType=9 called by com.google.android.gms (2183/10029)
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=22 [22][5][0]
,I/CheckinRequestBuilder( 2183): Classify the device as Phone.
,I/CheckinTask( 2183): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2183): Checking schedule, now: 1453034321978 next: 1453557258973
,I/CheckinService( 2183): active receiver: disabled
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,I/CheckinService( 2183): Checking schedule, now: 1453034322004 next: 1453557258973
,I/CheckinService( 2183): active receiver: disabled
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2183, uid=10029, userID:0
,D/CheckinService( 2183): Recording last checkin time for package unspecified as 1453034322008
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(429ea708): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (2183/10029)
D/PMS     (  915): acquireWL(43038360): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7db3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4598): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/PMS     (  915): acquireWL(4426f0a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  915): releaseWL(43038360): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: starting a change hold
,D/PMS     (  915): releaseWL(4426f0a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(435e6778): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(435e6778): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4598): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.facebook.katana (4598/10027)
,D/PMS     (  915): releaseWL(43b26540): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  915): acquireWL(42661150): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4578 10154 null
,W/ContextImpl( 4578): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4578, uid=10154, userID:0
,I/MusicLeanback( 4578): Conditions not met for autocaching.
,I/MusicLeanback( 4578): Stop autocaching.
,W/ContextImpl( 4578): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  915): releaseWL(42661150): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  915): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [4][0][0]
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1526): service - handleMessage() stop self
,D/AutoSetting( 1526): service - onDestroy() END
,D/AutoSetting( 1526): service - handleMessage() quit looper
,I/ActivityManager(  915): Killing 4356:com.htc.backup/1000 (adj 15): empty #17
D/Process (  915): killProcessQuiet, pid=4356
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  915): Recipient 4356
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4678): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  915): killProcessQuiet, pid=4320
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4320:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4320
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  915): killProcessQuiet, pid=3951
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 3951:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 3951
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  915): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4774 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1277): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/Launcher( 1277): Deferring update until onResume
,D/Launcher( 1277): waitUntilResume // bindAppsUpdated
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "smsto"
,I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/ExternalAccountType( 1343): Unsupported attribute readOnly
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4774): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4774): MmsConfig.loadMmsSettings
,W/dalvikvm( 4774): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4774): VFY: unable to resolve instance field 36
,W/dalvikvm( 4774): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4774): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  915): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4797 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4774, uid=10111, userID:0
,W/Settings( 4774): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4797): onCreate
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
,I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
V/GetPrviateResource( 4797): GetPrviateResource
,V/GetPrviateResource( 4797): GetPrviateResource
,D/MmsCustomizationProvider( 4797): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4774, uid=10111, userID:0
I/PackageManager(  915):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4774, uid=10111, userID:0
D/PMS     (  915): acquireWL(437dc7f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4774 10111 null
,D/MmsCustomizationProvider( 4797): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/[PluginManager]RegisterService( 1331): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1331): handle notify Blinkfeed plugin client changed
I/Babel   ( 4774): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4774): MmsConfig.loadFromDatabase
I/ActivityManager(  915): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  915): Resuming delayed broadcast
D/CaptivePortalTracker(  915): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  915): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  915): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,E/Babel   ( 4774): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4774): MmsConfig.loadFromResources
,I/ActivityManager(  915): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/Babel   ( 4774): canonicalizeMccMnc: invalid mccmnc nullnull
I/IcingCorporaProvider( 2859): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Babel   ( 4774): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
W/PackageManager(  915): Unable to load service info ResolveInfo{443329e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ProviderInstaller( 4774): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  915): acquireWL(4313dc80): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(4313dc80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(437dc7f8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  915): acquireWL(425c2bc8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/Process (  915): killProcessQuiet, pid=4373
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4373:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/MessageCustFlag( 4797): sense_version=6.0
,D/BTAccessoryUtil( 4797): createReceiver
,D/BTAccessoryUtil( 4797): registerReceiver return intent = null
D/MessageCustFlag( 4797): sku_id=99
,W/SystemReader( 4797): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  915): Recipient 4373
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Messaging( 4797): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4797): networkCode: 
,D/MessageCustFlag( 4797): sku_id=99
D/MmsConfig( 4797): SIE smsPri: null
,D/MmsConfig( 4797): networkCode: 
,D/HtcTelephonyCapability( 4797): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4797): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4797): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4797): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  915): releaseWL(425c2bc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  915): acquireWL(42a9a7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42a9a7b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,D/PMS     (  915): acquireWL(436a2990): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/dalvikvm-heap( 4076): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
D/PMS     (  915): acquireWL(44214e20): PARTIAL_WAKE_LOCK  AsyncService 0x1 4076 10160 null
,I/dalvikvm-heap( 4076): Grow heap (frag case) to 16.945MB for 1821008-byte allocation
D/PMS     (  915): releaseWL(436a2990): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(435c83f8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(44214e20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  915): releaseWL(435c83f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,I/ActivityManager(  915): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  915): acquireWL(43133460): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(43133460): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,D/PMS     (  915): acquireWL(4373c8c8): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  915): releaseWL(4373c8c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  915): Resuming delayed broadcast
,D/RemoteDisplayProvider(  915): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  915): start
,D/PMS     (  915): acquireWL(44285250): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2183): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  915): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  915): releaseWL(44285250): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(438d7370): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Icing   ( 2183): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2859): UpdateCorporaTask done [took 371 ms] updated apps [took 371 ms] 
I/ActivityManager(  915): Resuming delayed broadcast
,D/LocationProviderProxy(  915): applying state to connected service
D/PMS     (  915): acquireWL(446886a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(446886a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  915): applying state to connected service
,D/PMS     (  915): acquireWL(44349eb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(44341c58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(44341c58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(44349eb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(443369a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(443369a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b6ccd8 +
,I/Prism.WidgetManager( 1277): onLoadItems() +
,I/ActivityManager(  915): Waited long enough for: ServiceRecord{42f06ec0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/Icing   ( 2183): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2183): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  915): releaseWL(438d7370): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1277): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1277): onLoadItems() -
,I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b6ccd8 -
,D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1245): -- N1 =0
,D/PhoneApp( 1245): -- N2 =0
,D/PhoneApp( 1245): -- N3 =0
,D/Messaging( 4797): mNeedToUpdateDate2 start
,D/MmsConfig( 4797): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4797): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4797): 
D/MmsAsyncWorkHandler( 4797): HM tk = 20001
D/ReportIndicatorCache( 4797): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4797): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41aea3e8
,I/Messaging( 4797): mccmnc> 
D/DraftCache( 4797): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4797): [DraftCache/1] refresh
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4797): networkCode: 
,D/Messaging( 4797): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4797): HtcWrapEnvironment.getSupportedStorages() >1
D/MessageCustFlag( 4797): sense_version=6.0
D/PhoneStorageUtil( 4797): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4797): createReceiver
,D/Jerry   ( 4797): start to preload cursor >>>>>>>
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/TelephUtils( 1245): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1245): Update uri=content://mms, match=0
,V/MmsProvider( 1245): selection=st=129 AND m_type!=134
,D/Messaging( 4797): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4797): TransactionService is going to be woken up.
,D/Messaging( 4797): mNeedToUpdateDate2: false
,V/TransactionService( 4797): 1-Creating TransactionService
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1245): sku_id=99
V/TransactionService( 4797): onStartCommand: 1
,D/MmsSystemEventReceiver( 4797): unRegisterForConnectionStateChanges
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1245):  phoneType = -1
V/TransactionService( 4797): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4797): Loading previous transactions.
,D/DraftCache( 4797): [DraftCache/475] rebuildCache
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1245): device_type: 1
D/TransactionService( 4797): Force set service start id to 1
V/TransactionService( 4797): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4797): unRegisterForConnectionStateChanges
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
V/TransactionService( 4797): Destroying TransactionService
,D/TransactionService( 4797): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4797): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 4797): ViewCache CreatePreload
,D/Messaging( 4797): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4797): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1245): URI_DRAFT
,D/Cust_MMSMS( 4797): _has_set_default_values_2=true
,D/DraftCache( 4797): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4797): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4797): 
D/MmsAsyncWorkHandler( 4797): HM tk = 20002
,D/MsgPreferenceUtils( 4797): def_index: 0
,D/MsgPreferenceUtils( 4797): globalIndex = 1
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1245): sku_id=99
,D/MsgPreferenceUtils( 4797): phone state: true
D/MsgPreferenceUtils( 4797): sd state: false
,D/MsgPreferenceUtils( 4797): vIndex = 0
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1245): sku_id=99
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4774): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  915): acquireWL(43a7d6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{43ea51f8: PendingIntentRecord{426c57d0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126036, Int=0
,D/PMS     (  915): releaseWL(43a7d6f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(438102f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/PMS     (  915): acquireWL(425da000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(425da000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(438102f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(423b0510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(423b0510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(41f84a90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/PMS     (  915): acquireWL(42357e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(425a3cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1225): Vacuum at: now=1453034335974 tag=VacuumService
,D/PMS     (  915): releaseWL(41f84a90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42357e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4253ef50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(4253ef50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(424cde38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  915): releaseWL(425a3cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/PMS     (  915): releaseWL(424cde38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(42543db8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(42543db8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4318a100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
D/PMS     (  915): releaseWL(4318a100): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(437888b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/PMS     (  915): acquireWL(44285b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(44285b70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(42a2e3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(437888b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(434481e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(434481e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 4863 seconds from now (1453034336524)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4335 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 259
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  915): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/PMS     (  915): releaseWL(42a2e3e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43572628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(43572628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(4434b4d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
,W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1189): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(4434b4d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(43394b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=130304, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(43394b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42681c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  915): releaseWL(42681c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  915): updateBatteryInfo
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=98
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(438ed870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{4271db90: PendingIntentRecord{424b93d0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136768, Int=0
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  915): releaseWL(438ed870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1331): service - mHandler: update timezone
,D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1526): service - onCreate()
,W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1526): service - mHandler: update timezone
,D/DotMatrix( 1567): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  915): batLight: plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c80000
D/qdlights(  915): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1526): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1526): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1121): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1121): release indeterminate drawable android.widget.OnDemandProgressBar{41ea0ef0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1121): com.htc.htclocationservice 2 7 3 11
,D/AutoSetting( 1331): service - mHandler: update timezone
,D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1526): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1331): service - handleMessage() stop self
D/DotMatrix( 1567): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
W/ActivityManager(  915): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  915): batLight: plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c80000
D/qdlights(  915): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1526): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1526): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1526): service - mHandler: update timezone
D/AutoSetting( 1331): service - handleMessage() quit looper
D/AutoSetting( 1331): service - onDestroy() END
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1526): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1526): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1526): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1567): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1121): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1121): release indeterminate drawable android.widget.OnDemandProgressBar{41f0fd08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1121): com.htc.htclocationservice 2 7 3 11
,D/GpsLocationProvider(  915): ALARM_XTRA_TIMEOUT
D/PMS     (  915): acquireWL(43ee0db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
V/AlarmManager(  915): sending alarm PendingIntent{41d809b8: PendingIntentRecord{41d88898 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142405, Int=0
D/PMS     (  915): acquireWL(4303da58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 915 1000 null
D/GpsLocationProvider(  915): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  915): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  915): releaseWL(43ee0db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  915): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  915): [NET] getaddrinfo-,err=8
D/libc    (  915): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  915): [NET] getaddrinfo-, 1
,D/libc    (  915): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cbd8 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  915): [NET] getaddrinfo_proxy-, success
,I/global  (  915): call createSocket() return a new socket.
D/libc    (  915): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  915): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  915): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  915): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  915): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  915):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  915): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  915): acquireWL(4315e8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(4315e8c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PowerUI ( 1121): closing low battery warning: level=98
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  915): BroadcastReceiver::onReceive-
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  915): releaseWL(4303da58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  915): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  915): killProcessQuiet, pid=4411
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4411:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4411
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  915): Waited long enough for: ServiceRecord{42478758 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  915): acquireWL(42678bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41cb01e0: PendingIntentRecord{424d47a8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=166306, Int=0
,D/PMS     (  915): acquireWL(44338cc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 915 1000 null
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (915/1000)
,D/PMS     (  915): releaseWL(42678bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4374bc50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 915 1000 null
,D/PMS     (  915): releaseWL(44338cc0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  915): releaseWL(4374bc50): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1526): service - handleMessage() stop self
,D/AutoSetting( 1526): service - onDestroy() END
,D/AutoSetting( 1526): service - handleMessage() quit looper
,D/Process (  915): killProcessQuiet, pid=4425
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  915): Killing 4425:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  915): Recipient 4425
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(42530780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10027}
,V/AlarmManager(  915): sending alarm PendingIntent{42d3ba48: PendingIntentRecord{437c1ea8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174388, Int=0
,D/PMS     (  915): releaseWL(42530780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  915): acquireWL(43cf0af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=190303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1277): Grow heap (frag case) to 12.724MB for 50416-byte allocation
D/PMS     (  915): releaseWL(43cf0af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42d5c3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/PMS     (  915): releaseWL(42d5c3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1121): closing low battery warning: level=98
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(425d7248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(425d7248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=99
,D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  915): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(44315ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=250304, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(44315ec8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43738600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43738600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(4262bc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=310303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(4262bc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43909768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43909768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4484): TAP version 13
I/jxcore-log( 4484): 
,I/jxcore-log( 4484): # setup
I/jxcore-log( 4484): 
,I/jxcore-log( 4484): # multiplex can send data
I/jxcore-log( 4484): 
,I/jxcore-log( 4484): # teardown,
I/jxcore-log( 4484): 
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(42b0c0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=370303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(42b0c0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(438bfd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(438bfd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  915): acquireWL(44357020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/BatteryService(  915): n_update end
V/NotificationService(  915): batLight: Full, plugged
V/LightsService(  915): setLight #8: color=#c8c800
D/qdlights(  915): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  915): setLight #8: color=#c800
D/qdlights(  915): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  915): [LedInfo] has indicator attribute
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  915): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderNotification, total:0
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1605): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PMS     (  915): releaseWL(44357020): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
,W/ContextImpl( 4537): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3836): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3836): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3836): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3836): Cust_ConnectToPC   : spcsc>false
D/        ( 3836): Cust_ConnectToPC   : IPT>true
D/        ( 3836): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3836): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3836): Index of the first 1 = -1
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 3836): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3836): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3836): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3836): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3836): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/SmartNS_Utility( 3836): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(442a9310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=430304, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(442a9310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(43979100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43979100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(424e4f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
I/BatteryService(  915): n_update end
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(424e4f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1121): closing low battery warning: level=100
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  915): acquireWL(426287b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=490304, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(426287b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4434dae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4434dae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  915): acquireWL(43e786c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=550303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1277): Grow heap (frag case) to 12.649MB for 50416-byte allocation
,D/PMS     (  915): releaseWL(43e786c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42d4b8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  915): updateBatteryInfo
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(42d4b8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(430a4e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=610304, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(430a4e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4355a4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  915): releaseWL(4355a4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
,I/HtcPowerSaver(  915): >> updateStatus
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
,D/ContactMessageStore( 1245): start background delete task...
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,I/ActivityManager(  915): Killing 4148:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  915): killProcessQuiet, pid=4148
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  915): Recipient 4148
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  915): acquireWL(443505c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=670303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(443505c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(437111c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/UsbnetService(  915): BroadcastReceiver::onReceive+
D/UsbnetService(  915): onReceive BATTERY_CHANGED
D/UsbnetService(  915):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  915): BroadcastReceiver::onReceive-
,I/IntentController( 1121): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1121): closing low battery warning: level=100
D/PowerUI ( 1121): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 98, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  915): updateBatteryInfo
D/PMS     (  915): releaseWL(437111c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1567): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1567): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  915): runPSCheck
D/HtcPowerSaver(  915): Checking...
I/HtcPowerSaver(  915): >> updateStatus
,I/HtcPowerSaver(  915): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  915): << updateStatus
,I/BatteryController( 1121): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  915): acquireWL(43e48738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(43e48738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(44308c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=730303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(44308c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(433c14b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(433c14b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(425b98e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=790303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(425b98e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(437157e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(437157e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(425867a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=850304, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(425867a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4255c6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4255c6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(42669e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=910303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(42669e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4422f798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4422f798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(4265b6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=970303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(4265b6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4331d368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4331d368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(4250d128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41d446a0: PendingIntentRecord{4246da60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786202, Int=0
,D/ConnectivityService(  915): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  915): Done.
,D/ConnectivityService(  915): Setting timer for 720seconds,
,I/ActivityManager(  915): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4904 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  915): sending alarm PendingIntent{4231ab68: PendingIntentRecord{4244c020 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453034421490, Int=10800000
,V/AlarmManager(  915): sending alarm PendingIntent{42646550: PendingIntentRecord{42688298 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453035141913, Int=900000
,W/ContextImpl( 4537): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,V/AlarmManager(  915): sending alarm PendingIntent{438a8e48: PendingIntentRecord{438c7008 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453035216387, Int=0
,D/PowerUsageService( 4537): call getInstance()
,D/SmartSyncUtils( 4537): isEpsOn(), nState = 0
,D/PMS     (  915): releaseWL(4250d128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 4537): MY_DEBUG = false
D/PMS     (  915): acquireWL(433b3620): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4537 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4537): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4537): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4537): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4537): SettingOnTime = 1453096800000, randomSettingOnTime = 1453094515000
,D/SmartSyncScreenOnOffTimeReceiver( 4537): SettingOffTime = 1453082400000, randomSettingOffTime = 1453089546000
,D/SmartSyncScreenOnOffTimeReceiver( 4537): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4537): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4537): bNightModeTurnOffOnce = false
D/PMS     (  915): releaseWL(433b3620): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/ConnectivityService(  915): getActiveNetworkInfo called by com.htc.aurora (4904/10049)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,W/BatSI   (  915): Couldn't get kernel wake lock stats
,D/Process (  915): killProcessQuiet, pid=4455
,D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  915): Killing 4455:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  915): Recipient 4455
,D/PMS     (  915): acquireWL(426ceea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  915): sending alarm PendingIntent{4438be28: PendingIntentRecord{425be868 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1012613, Int=0
,D/PMS     (  915): acquireWL(42602b00): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(42602b00): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): releaseWL(426ceea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  915): acquireWL(42589740): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  915): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  915): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  915): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  915): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024440
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024766
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024912
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024917
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024921
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360024924
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026281
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360026297
W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360029217
,W/AlarmManager(  915): Converted elapesd time is over 1 year! when = 315360030354
,D/PMS     (  915): releaseWL(42589740): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  915): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  915): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  915): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=3 [235][9][0]
,D/WifiNative-wlan0(  915): doString: SIGNAL_POLL
W/WifiHW  (  915): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1189): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1189): nl80211: survey data missing!
E/wpa_supplicant( 1189): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1189): environment dirty rate=0 [0][0][0]
,D/PMS     (  915): acquireWL(424c5a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1030303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(424c5a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42432630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(42432630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(423c5580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1090303, Int=0
I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(423c5580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(422eebd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(422eebd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(41d91060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1150303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(41d91060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(42581678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(42581678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  915): acquireWL(424784c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1210303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(424784c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4241b5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4241b5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  915): acquireWL(4228c100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 915 1000 WorkSource{1000}
,V/AlarmManager(  915): sending alarm PendingIntent{41ad7fa0: PendingIntentRecord{42014588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1270303, Int=0
,I/IntentController( 1121): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  915): releaseWL(4228c100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  915): acquireWL(4370ecc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  915): n_update end
,D/PMS     (  915): releaseWL(4370ecc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4923): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4923): ====startRecUseTime====
D/htc.customization.log.level( 4923):  is 
W/CustomizationLogLevel( 4923): Level value is invalid, use default level 2
D/CustomizationManager( 4923):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4923): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4923): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4923): Parsing tag category name = system
I/CustomizationCIDLoader( 4923): Parsing tag category name = application
I/CustomizationCIDLoader( 4923): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4923): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4923): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4923): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4923): Parsing tag category name = Settings
D/CustomizationManager( 4923):  Read CID file spent 0.158 (s)
D/CustomizationManager( 4923):  All configurations done spent 0.159 (s)
W/HtcNativeFlag( 4923): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4923): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4923): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4923): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  915): deletePackageAsUser: pkg=com.test.thalitest, pid=4923, uid=2000 user=0
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  915): killProcessQuiet, pid=4484
D/Process (  915): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  915): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  915): Killing 4484:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  915):   Force finishing activity ActivityRecord{42554038 u0 com.test.thalitest/.MainActivity t2}
W/asset   (  915): Copying FileAsset 0x5f694cd8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
E/JavaBinder(  915): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  915): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1213): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  915): Got RemoteException sending setActive(false) notification to pid 4484 uid 10389
W/PackageSettings(  915): Skipping PackageSetting{421bd548 com.example.hello/10397} due to missing metadata
I/ActivityManager(  915): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1121): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1567): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1567): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
D/PMS     (  915): acquireWL(43646e68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(43646e68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/InputDispatcher(  915): channel '42538198 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  915): channel '42538198 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  915): Client connection lost with reason: 4
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1277): Deferring update until onResume
D/Launcher( 1277): waitUntilResume // bindAppsRemoved
W/InputDispatcher(  915): Attempted to unregister already unregistered input channel '42538198 com.test.thalitest.MainActivity (s)'
I/WindowState(  915): WIN DEATH: Window{42538198 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/[PluginManager]RegisterService( 1331): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/Prism.PackageStateRece_( 1277): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/[PluginManager]RegisterService( 1331): handle notify Blinkfeed plugin client changed
I/WindowManager(  915): WINDOW DIED Window{42538198 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/IcingCorporaProvider( 2859): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  915): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4939 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "sms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/InputMethodManagerService(  915): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  915):   Scheme: "smsto"
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mms"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  915):   Action: "android.intent.action.SENDTO"
I/PackageManager(  915):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  915):   Scheme: "mmsto"
I/PackageManager(  915): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  915): acquireWL(44322f50): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): releaseWL(44322f50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  915): acquireWL(43e483a0): PARTIAL_WAKE_LOCK  Icing 0x1 2183 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2859): UpdateCorporaTask done [took 519 ms] updated apps [took 519 ms] 
E/SQLiteDatabase( 4939): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4939): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4939): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4939): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4939): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4939): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4939): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4939): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4939): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4939): threadid=11: thread exiting with uncaught exception (group=0x416a7e30)
E/ActivityManager(  915): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4939): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4939): Process: com.google.android.apps.docs, PID: 4939
E/AndroidRuntime( 4939): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4939): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4939): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4939): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4939): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4939): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4939): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4939): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4939): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4939): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4939): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4939): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4939): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4939): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4939): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4939): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4939): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4939): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4939): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4939): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4939): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4939): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4939): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4939): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4939): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4939): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4939): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4939): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4939): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4939): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4939): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4939): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4939): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4939): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4939): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4939): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4939): 	at dalvik.system.NativeStart.main(Native Method)
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  915): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4958 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4939): killProcess, pid=4939
D/Process ( 4939): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  915): Recipient 4939
I/ActivityManager(  915): Process com.google.android.apps.docs (pid 4939) has died.
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4958): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  915): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4971 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4958): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4958): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4958): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4958): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4958): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4958): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4958): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4958): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4958): threadid=10: thread exiting with uncaught exception (group=0x416a7e30)
E/AndroidRuntime( 4958): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4958): Process: com.android.keychain, PID: 4958
E/AndroidRuntime( 4958): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4958): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4958): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4958): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4958): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4958): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4958): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4958): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4958): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4958): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  915): App crashed! Process: com.android.keychain
D/ErrorReport(  915): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4971): getInstance(Context context)
D/Process ( 4958): killProcess, pid=4958
D/Process ( 4958): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  915): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  915): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453035525156.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Recipient 4958
I/ActivityManager(  915): Process com.android.keychain (pid 4958) has died.
W/ActivityManager(  915): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4971): getInstance(Context context)
D/AppTag  ( 4971): onCreate()
D/PMS     (  915): acquireWL(43586830): PARTIAL_WAKE_LOCK  AsyncService 0x1 4076 10160 null
D/PMS     (  915): releaseWL(43586830): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4101): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2183): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2183): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2183): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2183): Module APK com.google.android.play.games already loaded
I/ActivityManager(  915): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2183): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2183): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e88fa88
E/SQLiteDBG( 2183): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65668800
W/dalvikvm( 2183): threadid=45: thread exiting with uncaught exception (group=0x416a7e30)
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
E/SQLiteDatabase( 2183): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  915): App crashed! Process: com.google.android.gms
E/SQLiteOpenHelper( 2183): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2183): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2183): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2183): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2183): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2183): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2183): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2183): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteLog( 2183): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/Process ( 2183): killProcess, pid=2183
D/gH_CompatibleDatabase( 2183): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2183): threadid=49: thread exiting with uncaught exception (group=0x416a7e30)
D/Process ( 2183): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime_2_crash( 2183): crash in the same process: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime_2_crash( 2183): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime_2_crash( 2183): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime_2_crash( 2183): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime_2_crash( 2183): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime_2_crash( 2183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime_2_crash( 2183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime_2_crash( 2183): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime_2_crash( 2183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41b6ccd8 +
I/Prism.WidgetManager( 1277): onLoadItems() +
I/ActivityManager(  915): Recipient 2183
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  915): Process com.google.android.gms (pid 2183) has died.
D/WifiService(  915): Client connection lost with reason: 4
D/PMS     (  915): handleWLDeath(43e483a0): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
I/ActivityManager(  915): Resuming delayed broadcast
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
E/SQLiteLog( 1359): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1359): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fef820
W/dalvikvm( 1359): threadid=1: thread exiting with uncaught exception (group=0x416a7e30)
E/AndroidRuntime( 1359): FATAL EXCEPTION: main
E/AndroidRuntime( 1359): Process: com.google.process.gapps, PID: 1359
E/AndroidRuntime( 1359): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1359): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1359): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1359): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1359): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1359): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1359): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1359): 	... 10 more
E/ActivityManager(  915): App crashed! Process: com.google.process.gapps
W/PackageManager(  915): Unable to load service info ResolveInfo{42aeeec0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/DropBoxManagerService(  915): Can't write: system_app_crash
E/DropBoxManagerService(  915): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1359): killProcess, pid=1359
D/Process ( 1359): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  915): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5000 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5000): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5000 dbg=false s=true
I/DeviceManagement( 5000): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5000): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5000): WorkflowService: Starting workflow service
I/DeviceManagement( 5000): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b09f18] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5000): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5000): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5000): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5000): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  915): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5014 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5000): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5000): SessionStateController: Checking invariants...
I/DisplayManagerService(  915): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  915): Client connection lost with reason: 4
I/ActivityManager(  915): Recipient 1359
I/ActivityManager(  915): Process com.google.process.gapps (pid 1359) has died.
W/ActivityManager(  915): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20754ms
D/Documents( 5014): Loading roots for com.android.providers.downloads.documents
D/Documents( 5014): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5014): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5014): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5014): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5014): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5014): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5014): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5014): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5014): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5014): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5014): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5014): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5014): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5014): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5014): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5014): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5014): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5014): threadid=1: thread exiting with uncaught exception (group=0x416a7e30)
E/AndroidRuntime( 5014): FATAL EXCEPTION: main
E/AndroidRuntime( 5014): Process: com.android.documentsui, PID: 5014
E/AndroidRuntime( 5014): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5014): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5014): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5014): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5014): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5014): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5014): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5014): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5014): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5014): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5014): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5014): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5014): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5014): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5014): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5014): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5014): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5014): 	... 10 more
I/ActivityManager(  915): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5028 uid=10023 gids={50023, 1028, 1015, 1023}

```
