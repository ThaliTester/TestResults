#### Test 54312298239818e_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  984): doBoolean: SignalStrength 97
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  984):    returned true
E/cutils-trace( 4396): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4396): ====startRecUseTime====
D/htc.customization.log.level( 4396):  is 
W/CustomizationLogLevel( 4396): Level value is invalid, use default level 2
D/CustomizationManager( 4396):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4396): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4396): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4396): Parsing tag category name = system
I/CustomizationCIDLoader( 4396): Parsing tag category name = application
I/CustomizationCIDLoader( 4396): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4396): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4396): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4396): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4396): Parsing tag category name = Settings
D/CustomizationManager( 4396):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4396):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4396): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4396): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4396): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4396): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  984): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  984): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  984): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  984): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  984): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  984): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  984): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4396
D/PMS     (  984): acquireHCC(43631078): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 984 1000 null
D/PMS     (  984): acquireHCC(43631d00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 984 1000 null
W/asset   (  984): Copying FileAsset 0x66a4bd98 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  984): @test_code: getHtcIntentFlag: 0 obj: 1130563952
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@423d3c40
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  984): acquireWL(436334c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 984 1000 null
I/ActivityManager(  984): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4407 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
W/asset   ( 4407): Copying FileAsset 0x5c8a2538 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4407): Binding Chromium to main looper Looper (main, tid 1) {4221c2e0}
I/LibraryLoader( 4407): Expected native library version number "",actual native library version number ""
I/chromium( 4407): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4407): Initializing chromium process, renderers=0
D/PMS     (  984): acquireWL(42b84ca0): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  984): acquireWL(42cea888): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
D/PMS     (  984): releaseWL(42b84ca0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  984): java.lang.Throwable: stack dump
D/BluetoothManagerService(  984): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@449348e0:true
W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  984): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  984): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  984): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4407): 1109597464: getState(). Returning 12
,I/Adreno-EGL( 4407): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4407): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4407): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4407): Local Branch: 
I/Adreno-EGL( 4407): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4407): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4407):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4407): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4407): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4407): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4407): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4407): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4407): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4407): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4407): CordovaWebView is running on device made by: HTC
,W/AwContents( 4407): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  984): Disable input method client, pid=1269
,I/InputMethodManagerService(  984): Enable input method client, pid=4407
W/ResourceType( 4407): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4407): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@422633c8, mServedView=org.apache.cordova.engine.SystemWebView{42229030 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  984): Displayed com.test.thalitest/.MainActivity: +364ms
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4407): nativeOnDraw failed; clearing to background color.
D/PMS     (  984): releaseWL(436334c0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4407): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4407): JniHelper::setJavaVM(0x41dd3010), pthread_self() = 1662962264
,D/JX-Cordova( 4407): jxcore cordova android initializing
,W/PluginManager( 4407): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.601MB for 144892-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 12.573MB for 733480-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 14.021MB for 1650320-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 15.435MB for 2475476-byte allocation
,I/dalvikvm-heap( 4407): Grow heap (frag case) to 17.455MB for 3713210-byte allocation
,W/CpuWake (  984): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  984): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  984): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  984): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  984): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  984): <<release mCpuPerf_Freq wakelock
,D/PMS     (  984): releaseHCC(43631078): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  984): releaseHCC(43631d00): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4407): Initializing JXcore engine
,W/jxcore-log( 4407): JXcore engine is ready
,W/jxcore-log( 4407): Starting JXcore engine
,W/jxcore-log( 4407): Platform android
W/jxcore-log( 4407): 
,W/jxcore-log( 4407): Process ARCH arm
W/jxcore-log( 4407): 
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  984): doBoolean: SignalStrength 97
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  984):    returned true
,I/jxcore-log( 4407): JXcore Cordova bridge is ready!
I/jxcore-log( 4407): 
,W/jxcore-log( 4407): JXcore engine is started
,I/Choreographer( 4407): Skipped 134 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4407): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  984): releaseWL(42cea888): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  984): Going to sleep due to screen timeout...
,I/SensorManager(  984): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@429337f8
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  984): disable: get sensor name = CM36282 Light sensor
W/SensorService(  984): pid=984, uid=1000
W/SensorService(  984): Active sensors: size = 2
W/SensorService(  984): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  984): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  984): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@429337f8, eanble = 0, strlen(mName) = 59
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  984): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426ff6b0
W/SensorService(  984): Listener[1] = com.htc.smartdim.sensor_eye@42adfe90
,W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  984): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  984): Couldn't get kernel wake lock stats
V/LightsService(  984): setLight #2: color=#0
D/qdlights(  984): set_light_buttons_func: on=0 brightness=0
V/LightsService(  984): setLight #0: color=#0
,W/PMS     (  984): mWirelessDisplayManager is null
D/WirelessDisplayService(  984): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  984): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  984): Excessive delay in blankDisplay() while turning screen off: 312ms
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,V/KeyguardServiceDelegate(  984): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4319abd8),
D/PMS     (  984): nativeSetInteractive:false,
D/PMS     (  984): nativeSetInteractive:false done
D/PMS     (  984): nativeSetAutoSuspend:true
D/PMS     (  984): nativeSetAutoSuspend:true done
D/HABCtrl (  984): TPE algorithm. remove timeout.
D/PMS     (  984): OOBE c monitor 11
I/InputManager(  984): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  984): screenObserver, isScreenOn=false
D/PMN     (  984): wakingUp
D/NfcService( 1253): applyRouting -2
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  984): acquireWL(42b69828): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  984): releaseWL(42b69828): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/InputMethodManagerService(  984): Disable input method client, pid=4407
,V/KeyguardServiceDelegate(  984): **** SHOWN CALLED ****
D/WirelessDisplayService(  984): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  984): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  984): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  984): No lock screen! windowToken=null
D/PMN     (  984): onScreenOn
D/PMS     (  984): acquireWL(42add858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/MtpService( 2379): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2379): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting - 0
,D/AutoSetting( 1304): receiver - intent: android.intent.action.USER_PRESENT
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(42add858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  984): batLight: Full, plugged
V/LightsService(  984): setLight #8: color=#c8c800
D/qdlights(  984): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  984): setLight #8: color=#c800
D/NfcService( 1253): applyRouting -2
D/WirelessDisplayService(  984): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  984): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  984): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/TetherSettings( 3805): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3805): Cust_ConnectToPC   : Internet_Sharing>true
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/        ( 3805): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3805): Cust_ConnectToPC   : spcsc>false
D/        ( 3805): Cust_ConnectToPC   : IPT>true
D/        ( 3805): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3805): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3805): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3805): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3805): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1304): service - onCreate()
D/qdlights(  984): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute
D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  984): acquireWL(4290b728): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  984): releaseWL(4290b728): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  984): ACTION_SCREEN_ON
I/AlarmManager(  984): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  984): [AlarmQueuing] done recovering
I/AlarmManager(  984): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  984): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/WifiDataStallTracker(  984): onReceive: action=android.intent.action.SCREEN_ON
D/AutoSetting( 1304): service - AddressCache: using context: com.htc.Weather
,D/WifiDataStallTracker(  984): startDataStallAlarm: tag=21812 delay=15s
,I/PSReceiver( 3805): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  984): request 42b61320 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  984): provider request: passive ProviderRequest[ON interval=0]
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
W/ContextImpl( 3805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
I/SmartNS_PSService( 3805): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3805): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  984): doBoolean: SET_SCREEN_ON 1
I/SmartNS_PSService( 3805):  defaultType:0
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
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
D/WifiNative-wlan0(  984):    returned true
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1119): stop update clock
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  984): batLight: Full, plugged
V/LightsService(  984): setLight #8: color=#c8c800
D/qdlights(  984): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  984): setLight #8: color=#c800
D/qdlights(  984): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute
D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  364): ParamSet string: screen_state=on
D/WirelessDisplayService(  984): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/NetworkPolicy(  984): updateScreenOn: false
,I/ActivityManager(  984): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4463 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 4463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  984): acquireWL(4355d368): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(4355d368): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): acquireWL(43556258): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(42d7e458): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4463 1000 null
,D/SmartSyncUtils( 4463): isEpsOn(), nState = 0
,D/PMS     (  984): releaseWL(43556258): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): onScreenOn: 1450743020018
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1775): onScreenOn: 1450743020018
,D/PMS     (  984): releaseWL(42d7e458): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/SensorManager(  984): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426ff6b0
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  984): pid=984, uid=1000
W/SensorService(  984): Active sensors: size = 2
W/SensorService(  984): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  984): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  984): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@426ff6b0, eanble = 0, strlen(mName) = 91
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  984): Listener[0] = com.htc.smartdim.sensor_eye@42adfe90
,W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4463): getMobilePolicyEnabled, result = true
D/PMN     (  984): goingToSleep
D/PMS     (  984): acquireWL(429e1628): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 984 1000 null
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  984): ACTION_SCREEN_OFF
I/AlarmManager(  984): [AlarmQueuing] screen off now: 
I/AlarmManager(  984): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  984): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  984): stopDataStallAlarm: current tag=21812 mDataStallAlarmIntent=PendingIntent{42afa0d8: PendingIntentRecord{42630878 android broadcastIntent}}
I/AlarmManager(  984): [AlarmQueuing] wifi connection: true
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/WifiNative-wlan0(  984): doBoolean: SET_SCREEN_ON 0
D/PMS     (  984): acquireWL(42c19e10): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 984 1000 null
,D/SmartSyncUtils( 4463): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4463): getMobilePolicyEnabled, result = true
W/ContextImpl( 4463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  984): New client listening to asynchronous messages
D/SmartSyncUtils( 4463): isEpsOn(), nState = 0
,I/jxcore-log( 4407): Toggling radios to true
I/jxcore-log( 4407): 
,D/BluetoothAdapter( 4407): enable(): BT is already enabled..!
,D/WifiManager( 4407): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  984): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  984): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  984): Settings:Agentvalue: 2
,W/Settings:Agent(  984): >> traceCallingStack()
W/Settings:Agent(  984): Process.myPid(): 984
W/Settings:Agent(  984): Process.myTid(): 1267
,W/Settings:Agent(  984): Process.myUid(): 1000
,W/Settings:Agent(  984): 
W/Settings:Agent(  984): 
W/System.err(  984): java.lang.Throwable: stack dump
W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  984): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  984): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  984): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  984): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  984): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  984): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  984): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  984): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  984): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  984): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  984): 
W/Settings:Agent(  984): << traceCallingStack(): 1(ms)
D/WifiManager( 4407): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4407): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  984): setWifiEnabled: true pid=4407, uid=10389
E/WifiService(  984): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  984): isSprintWifiRestricted(): false
I/WifiService(  984): isMdmWifiRestricted(): false
D/WifiSettingsStore(  984): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  984): New client listening to asynchronous messages,
I/jxcore-log( 4407): Radios toggled,
I/jxcore-log( 4407): 
D/BluetoothManagerService(  984): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4407): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4407): 
I/jxcore-log( 4407): Perf Test app loaded loaded
I/jxcore-log( 4407): 
I/Choreographer( 4407): Skipped 80 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4407): check test folder
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): found test : ./testFindPeers.js
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): found test : ./testSendData.js
I/jxcore-log( 4407): 
,I/jxcore-log( 4407): found test : ./testSendData2.js
I/jxcore-log( 4407): 
,E/jxcore  ( 4407): Error!: missing ) after argument list
E/jxcore  ( 4407): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
W/ResourceType( 4407): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4407): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42229030 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4407): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  984): releaseWL(429e1628): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0,
I/wpa_supplicant( 1180): SET_SCREEN_ON:Off
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
,I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0,
D/WifiNative-wlan0(  984): doBoolean: SignalStrength 97
D/WifiNative-wlan0(  984):    returned true,
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97,
D/WifiNative-wlan0(  984):    returned true
D/WifiStateMachine(  984): [ScoreAP] + current TXpacket:146, mTXpacketCount:146, avgLinkspeed:24,mAvgTxRate54
D/WifiStateMachine(  984): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB,
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50,
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/SensorManager(  984): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42adfe90
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  984): pid=984, uid=1000
,W/SensorService(  984): Active sensors: size = 1
W/SensorService(  984): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  984): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42adfe90, eanble = 0, strlen(mName) = 36
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  984): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  984): pid=984, uid=1000
W/SensorService(  984): Active sensors: size = 0
W/SensorService(  984): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42adfe90, eanble = 0, strlen(mName) = 36
,W/SensorService(  984): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  984): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42adfe90
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  364): ParamSet string: screen_state=off
E/ActivityThread(  984): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42b4bb38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  984): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42b4bb38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  984): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  984): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  984): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  984): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  984): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  984): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  984): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  984): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  984): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  984): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  984): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  984): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  984): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  984): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  984): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  984): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  984): 	at dalvik.system.NativeStart.main(Native Method)
D/NetworkPolicy(  984): updateScreenOn: false
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
,I/PhoneStatusBar( 1119): removeHeadsNotification.gc: 64
,D/PMS     (  984): acquireWL(42ba99f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] getTotalRam: 1873 Mb
D/PMS     (  984): releaseWL(42ba99f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1775): onScreenOff
D/PMS     (  984): acquireWL(4383bc20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(4383bc20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1304): service - mHandler: cancel location update
,D/AutoSetting( 1304): service -           changes count: 0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  984):    returned true
,D/WifiNative-wlan0(  984): doBoolean: DISCONNECT
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): TDLS: Tear down peers
,I/wpa_supplicant( 1180): wpa_driver_nl80211_disconnect(reason_code=3)
D/PMS     (  984): releaseWL(42c19e10): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1180): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1180): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  984): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  984): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  984): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  984): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180): TDLS: Remove peers on disassociation
D/HTCRequest(  984): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  984): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  984): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  984): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  984): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/HTCRequest(  984): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  984): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb74e1bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1180): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1180): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0,
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1180): State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  984): interfaceLinkStateChanged wlan0, false
D/Tethering(  984): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  984):    returned true
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiPerfLock(  984): release()
,D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  984): PerfLock released for exiting ConnectedState
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  984): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
D/Tethering(  984): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
,D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
,D/wpa_supplicant( 1180): Add randomness: count=5 entropy=0
D/Tethering(  984): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1180): Add randomness: count=6 entropy=1
D/Tethering(  984): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1180): State: DISCONNECTED -> DISCONNECTED
D/WifiNative-wlan0(  984):    returned true
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
,I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
D/wpa_supplicant( 1180): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1180): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
,D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1180): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): clear disabled list - type=1
,I/wpa_supplicant( 1180): No suitable network found
W/wpa_supplicant( 1180): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1180): State: DISCONNECTED -> INACTIVE
D/ConnectivityService(  984): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  984): acquireWL(4405c1b0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 984 1000 null
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  984): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  984):    returned true
D/Tethering(  984): [isWifi] getHotspotEnabled: false
D/WifiP2pService(  984): InactiveState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): InactiveState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pEnabledState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): InactiveState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@42ddfbe0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pEnabledState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@42ddfbe0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): DefaultState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@42ddfbe0 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  984): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  984): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  984): [RunningState] Stop DHCP
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
D/WifiStateMachine(  984): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  984): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  984): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  984): doBoolean: RECONNECT
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 1180): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 0
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 0
D/WifiDataStallTracker(  984): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 1
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): selected network = 1
D/WifiDataStallTracker(  984): stopDataStallAlarm: current tag=21813 mDataStallAlarmIntent=null
D/wpa_supplicant( 1180): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0xb74e34e8  current_ssid=0x0
D/wpa_supplicant( 1180): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1180): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1180): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1180): check if in concurrent case
I/wpa_supplicant( 1180): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1180): RSN: PMKSA cache search - network_ctx=0xb74e34e8 try_opportunistic=0
D/wpa_supplicant( 1180): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180): RSN: No PMKSA cache entry found
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1180): State: DISCONNECTED -> ASSOCIATING
,D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1180): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1180): nl80211: Unsubscribe mgmt frames handle 0xb74e2718 (mode change)
D/wpa_supplicant( 1180): nl80211: Subscribe to mgmt frames with non-AP handle 0xb74e2718
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb74e2718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1180):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180):   * freq=2412
D/wpa_supplicant( 1180):   * Auth Type 0
D/wpa_supplicant( 1180):   * WPA Versions 0x2
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1180): nl80211: Connect request send successfully
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/UsbnetStateTracker(  984): isAvailable+-
D/UsbnetStateTracker(  984): reconnect
D/UsbnetStateTracker(  984): isAvailable+-
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  984):    returned true
D/WifiStateMachine(  984): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  984): Enter handleNetworkDisconnect
D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiStateTracker(  984): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  984): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  984): Provision feature enable=false
D/ConnectivityService(  984): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  984): default: reconnect()
D/MDST    (  984): default: setTeardownRequested(false)
D/MDST    (  984): default: setEnableApn apnType =default , enable=true
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
D/WISPrService( 3805): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  984): doBoolean: DRIVER POWERMODE 0
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  984):    returned true
D/WISPrService( 3805): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  984): doBoolean: DRIVER BTCOEXMODE 2
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  984): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  984): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  984): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  984): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/WifiService(  984): New client listening to asynchronous messages
D/ConnectivityService(  984): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  984): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  984):    returned true
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
V/NativeCrypto( 1363): Read error: ssl=0x65f4dc18: I/O error during system call, Connection timed out
D/WifiP2pService(  984): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  984): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  984): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  984): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  984): handleConnectivityChange: resetting
D/ConnectivityService(  984): resetConnections(wlan0, 3)
D/WifiStateMachine(  984): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  984): Exit handleNetworkDisconnect
D/WifiNative-wlan0(  984): doBoolean: SET pno 1
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1180): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1180): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  984):    returned false
D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  984): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  984): doString: LIST_DONGLES
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
V/NativeCrypto( 1363): SSL shutdown failed: ssl=0x65f4dc18: I/O error during system call, Broken pipe
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  984): acquireWL(43e5b430): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
D/WifiStateTracker(  984): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  984): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (238) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-48
I/wpa_supplicant( 1180): tsf=0000000108919334
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-56
I/wpa_supplicant( 1180): tsf=0000000108919358
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ####
D/libc    (  357): [NET] entry_id:3   entry:0xb891f320  removed 
D/libc    (  357): [NET] entry_id:4   entry:0xb891efd8  removed 
D/libc    (  357): [NET] entry_id:1   entry:0xb891f428  removed 
D/libc    (  357): [NET] entry_id:5   entry:0xb891f240  removed 
D/libc    (  357): [NET] entry_id:2   entry:0xb891f0e8  removed 
D/libc    (  357): [NET] entry_id:6   entry:0xb891af60  removed 
D/libc    (  357): *************************
D/libc    (  357): *** DNS CACHE FLUSHED ***
D/libc    (  357): *************************
D/WifiStateMachine(  984): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -200, -1
V/ScoreHelper(  984): Only print Top 10 in ApScanList
V/ScoreHelper(  984):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  984):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  984): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  984): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  984):  + computeScore(NG700): 1
D/WifiStateMachine(  984): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
D/ConnectivityService(  984): flush DNS cache for net 1(wlan0)
D/WifiStateMachine(  984): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108919334, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  984): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 108919358, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  984): add 2 to mScanResults
D/Nat464Xlat(  984): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  984): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
D/WISPrService( 3805): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3805): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiStateMachine(  984): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/WifiManager( 1225): getScanResults enter 
D/WirelessDisplayService(  984): getDiscoveryDongleList
D/ConnectivityService(  984): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  984): acquireWL(4335eeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 984 1000 null
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): reportInetCondition for net -1, percentage: 0 by  (1363/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/WirelessDisplayService(  984): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WifiStateMachine(  984): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/WirelessDisplayService(  984): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  984): == begin of scan result ==
D/WifiStateMachine(  984): == (2) end of scan result ==
D/WifiStateMachine(  984): == begin of scan result ==
D/WifiStateMachine(  984): == (2) end of scan result ==
D/WifiStateMachine(  984): startScan Pid: 984 Uid 1000
D/WifiNative-wlan0(  984): doBoolean: SET pno 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  984):    returned true
D/WifiNative-wlan0(  984): doBoolean: SCAN
D/ConnectivityService(  984): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  984): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiNotificationController(  984): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
D/PMS     (  984): releaseWL(43e5b430): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  984): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1180): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1180): Failed to initiate AP scan
I/wpa_supplicant( 1180): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  984):    returned true
I//system/bin/ip(  357): RTNETLINK answers: No such process
I/logwrapper(  357): /system/bin/ip terminated by exit(2)
,D/WirelessDisplayService(  984): getDiscoveryDongleList
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
D/PMS     (  984): releaseWL(4335eeb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): mActiveDefaultNetwork: -1
,D/ConnectivityService(  984): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Connect event
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1180): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Add randomness: count=9 entropy=4
I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): TDLS: Remove peers on association
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1180): EAPOL: enable timer tick
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1180): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1180): Get randomness: len=32 entropy=5
D/Tethering(  984): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  984): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  984): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  984): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  984): interfaceStatusChanged wlan0, false
D/HTCRequest(  984): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
D/Tethering(  984): [isWifi] getHotspotEnabled: false
D/HTCRequest(  984): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  984): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  984): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  984): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  984): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  984): Enter handleAssociatedWithEvent
D/WifiStateMachine(  984): Associated
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  984): interfaceLinkStateChanged wlan0, true
D/Tethering(  984): interfaceStatusChanged wlan0, true
,D/Tethering(  984): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  984): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  984): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  984): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  984): updateConnectedAP...
,D/WifiApDatabaseHandler(  984): updateConnectedAP...
,I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb74e29f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  984): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f24b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1180):    broadcast key
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1180): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1180): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  984): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1180): set send_ind_to_ndc = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 1180): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1180): EAPOL authentication completed successfully
I/wpa_supplicant( 1180): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  984): interfaceLinkStateChanged wlan0, true
,D/Tethering(  984): interfaceStatusChanged wlan0, true
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  984): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  984): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  984): This record is existed, only update it...
D/WifiStateMachine(  984): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  984): updateConnectedAP...
,D/WifiStateMachine(  984): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  984): updateConnectedAP...,
,D/WifiStateMachine(  984): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  984): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false,
,D/WifiStateMachine(  984): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  984): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  984): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  984): This record is existed, only update it...
D/WifiStateMachine(  984): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  984): updateConnectedAP...
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  984): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  984): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  984): Provision feature enable=false
D/ConnectivityService(  984): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  984): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WISPrService( 3805): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiApDatabaseHandler(  984): updateConnectedAP...
,D/WISPrService( 3805): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  984): doBoolean: SET pno 0
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  984):    returned true
,D/WifiStateMachine(  984): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/DhcpStateMachine(  984): [StoppedState] Start DHCP
,D/WifiNative-wlan0(  984): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  984):    returned true
,D/WifiNative-wlan0(  984): doBoolean: DRIVER SETSUSPENDMODE 0
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  984):    returned true
D/WifiNative-wlan0(  984): doBoolean: DRIVER POWERMODE 1
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 1
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  984):    returned true
D/WifiNative-wlan0(  984): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1180): nl80211: Event message available
,D/wpa_supplicant( 1180): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1180): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  984):    returned null
E/WifiStateMachine(  984): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  984): doString: DRIVER WLS_BATCHING STOP,
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  984): handlePreDhcpSetup Held wake lock during DHCP,
D/PMS     (  984): acquireWL(4390d5d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 984 1000 null
D/WifiStateMachine(  984): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  984):    returned null
D/WifiP2pService(  984): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42c2d098 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42c2d098 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  984): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  984): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  984): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4503 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/CaptivePortalTracker(  984): DelayedCaptiveCheckState
,D/Tethering(  984): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/CaptivePortalTracker(  984): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
V/Tethering(  984): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  984): NoActiveNetworkState
,D/Tethering(  984): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  984): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  984): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  984): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  984): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTING
I/Tethering(  984): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  984): ipv4Default null
I/Tethering(  984): No IPv4 upstream interface, giving up.
,D/Tethering(  984): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.backuptransport (1570/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/PMS     (  984): acquireWL(42cc3610): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 984 1000 null
D/PMS     (  984): releaseWL(42cc3610): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,D/htcCheckinService(  984): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  984): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (4260/10100)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (4260/10100)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/wpa_supplicant( 1180): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1180): EAPOL: disable timer tick
,I/MusicStore( 4503): Database version: 95
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4503): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4503): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4503): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4503, uid=10154, userID:0
,D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
,D/MediaRouterService(  984): Client com.google.android.music (pid 4503): Registered
,D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
I/MediaRouter( 4503): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.music (4503/10154)
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (2379/10021)
,I/ActivityManager(  984): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4523 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4503): getSelectedRoute
,I/NetworkMonitor( 4503): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by com.google.android.music (4503/10154)
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4503, uid=10154, userID:0
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/ACRA    ( 4523): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  984): killProcessQuiet, pid=4196
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  984): acquireWL(4433bbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
I/ActivityManager(  984): Killing 4196:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMS     (  984): releaseWL(4433bbc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ACRA    ( 4523): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4523): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  984): Recipient 4196
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  984): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4523): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4523): Preparing secondary program dexes.
V/DexLibLoader( 4523): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4523): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4523): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4523): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped.
V/DexLibLoader( 4523): Creating class loader
V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped.
V/DexLibLoader( 4523): Creating class loader
V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped.
,V/DexLibLoader( 4523): Creating class loader
,V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped.
,V/DexLibLoader( 4523): Creating class loader
,V/DexLibLoader( 4523): Finished creating class loader
,V/DexLibLoader( 4523): Verifying classes from secondary dexes.
,D/DexLibLoader( 4523): DexLibLoader.ensureDexLoaded took 19 ms
,D/libc    (  984): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4523): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  984): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
,D/libc    (  984): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
,D/libc    (  984): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
,D/libc    (  984): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  984): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  984):    returned true
,D/WifiNative-wlan0(  984): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  984):    returned true
D/WifiNative-wlan0(  984): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  984):    returned true
,D/WifiStateMachine(  984): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  984): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  984): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  984): releaseWL(4390d5d8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  984): doBoolean: SignalStrength 97
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
,D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  984):    returned true
,D/WifiStateMachine(  984): gateway: /192.168.1.1
,D/WifiNative-wlan0(  984): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  984):    returned true
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent L2ConnectedState
,D/WifiStateMachine(  984): VerifyingLinkState enter
D/WifiStateMachine(  984): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
,D/WifiStateMachine(  984): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  984): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  984): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  984): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  984): WAN detection
D/WifiStateTracker(  984): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  984): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  984): Provision feature enable=false
D/ConnectivityService(  984): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  984): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  984): default: teardown()
D/MDST    (  984): default: setTeardownRequested(true)
D/MDST    (  984): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  984): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  984): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
D/MDST    (  984): default: setTeardownRequested(true)
D/ConnectivityService(  984): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  984): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b9c278
D/ConnectivityService(  984): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/WISPrService( 3805): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  984): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1180): Change stage from stage0 to stage3
D/WifiStateMachine(  984): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  984): syncGetConfiguredNetworks
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  357): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  984): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  984): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  357): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  984): handleConnectivityChange: resetting
D/Nat464Xlat(  984): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  984): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  984): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  984): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  984): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  984): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  984): acquireWL(43a40e60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 984 1000 null
,D/ConnectivityService(  984): getNetworkInfo networkType=1 called by  (984/1000)
D/WirelessDisplayService(  984): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
D/WirelessDisplayService(  984):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  984): releaseWL(43a40e60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I//system/bin/ip(  357): RTNETLINK answers: No such file or directory
I/logwrapper(  357): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  357): RTNETLINK answers: No such process
,I/logwrapper(  357): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  984): mActiveDefaultNetwork: WIFI
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4523): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4523): Verify
,D/WifiService(  984): New client listening to asynchronous messages
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4523): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4523): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  984): killProcessQuiet, pid=3841
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  984): Killing 3841:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 3841
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1304): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  984): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4574 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1304): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
D/AutoSetting( 1304): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1304): service - onStartCommand() check timezone in 30000
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4523): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4574): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4574): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4574): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4574): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  984): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4588 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  984): killProcessQuiet, pid=4100
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  984): Killing 4100:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,D/PMS     (  984): acquireWL(43ee2f38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(4333a8f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2151): Checkin interval check for package: unspecified last checkin: 1450742971750 min interval config: 0 actual interval: 52780
D/PMS     (  984): releaseWL(43ee2f38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2151): Checking schedule, now: 1450743024538 next: 1450743001718
,I/CheckinService( 2151): active receiver: enabled
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2151, uid=10029, userID:0
,I/CheckinService( 2151): Preparing to send checkin request
,I/EventLogService( 2151): Accumulating logs since 1450742968011
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
,I/ActivityManager(  984): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4603 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  984): killProcessQuiet, pid=4229
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  984): Killing 4229:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 4229
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinRequestBuilder( 2151): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  984): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2151): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  984): Recipient 4100
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.954MB for 84664-byte allocation
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.968MB for 28144-byte allocation
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4523): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4523): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4523): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4523): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4523): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4523): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4523): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4523): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
,W/dalvikvm( 4523): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4523): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4603): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.035MB for 39954-byte allocation
,D/ConnectivityService(  984): getNetworkInfo networkType=9 called by com.google.android.gms (2151/10029)
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.111MB for 79892-byte allocation
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
,V/WebViewChromiumFactoryProvider( 4603): Binding Chromium to main looper Looper (main, tid 1) {422172c8}
,I/LibraryLoader( 4603): Expected native library version number "",actual native library version number ""
,I/chromium( 4603): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4603): Initializing chromium process, renderers=0
,D/PMS     (  984): acquireWL(43de7f38): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
,D/PMS     (  984): acquireWL(43dd45a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 364 1013 null
,E/AudioManagerAndroid( 4603): BLUETOOTH permission is missing!
D/PMS     (  984): releaseWL(43de7f38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  984): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4633 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/PMS     (  984): releaseWL(4405c1b0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  984): NetTransition Wakelock for ConnectedState released by timeout
,W/dalvikvm( 4633): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,I/NSApplication( 4603): Starting up...
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4633): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4633): install
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/MultiDex( 4633): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
I/MultiDex( 4633): loading existing secondary dex files
I/MultiDex( 4633): load found 3 secondary dex files
,I/MultiDex( 4633): install done
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  984): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
I/AlarmManager(  984): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  984): bSetPropertyMultiRAB:false
D/Tethering(  984): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  984): NoActiveNetworkState
I/Tethering(  984): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  984): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  984): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  984): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  984): Found interface wlan0
D/Tethering(  984): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4503): type=WIFI subType= reason=null isConnected=true,
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.musicenhancer (3884/10053)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.backuptransport (1570/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (4260/10100)
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by com.google.android.music (4503/10154)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1340): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.backuptransport (1570/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.plus (4007/10160)
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (4260/10100)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
W/BroadcastQueue(  984): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43bef2c8 u0 ReceiverList{42d71460 4523 com.facebook.katana/10027/u0 remote:42e41cc8}}
W/BroadcastQueue(  984): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43bef2c8 u0 ReceiverList{42d71460 4523 com.facebook.katana/10027/u0 remote:42e41cc8}}
,W/BroadcastQueue(  984): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e68ac0 u0 ReceiverList{42e68a80 4523 com.facebook.katana/10027/u0 remote:438fddb0}}
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  984): DelayedCaptiveCheckState
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  984): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  984): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/Process (  984): killProcessQuiet, pid=4260
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.plus (4007/10160)
D/PMS     (  984): acquireWL(4429c310): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 984 1000 null
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
,I/ActivityManager(  984): Killing 4260:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/AccTypeManager( 1340): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1340): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(43e37c18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4633): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/GpsLocationProvider(  984): [handleMessage] UPDATE_NETWORK_STATE
W/dalvikvm( 4633): VFY: unable to resolve instance field 36
D/GpsLocationProvider(  984): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  984): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  984): ignore wifi update if we are not in OPENING or CLOSING
,W/dalvikvm( 4633): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  984): releaseWL(43e37c18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  984): releaseWL(4429c310): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
I/ActivityManager(  984): Recipient 4260
D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
V/JNIHelp ( 4633): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/ExternalAccountType( 1340): Unsupported attribute readOnly
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (2379/10021)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  984): acquireWL(42dd08f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(42dd08f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1304): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4574): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4574): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
,D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1304): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AutoSetting( 1304): Util - check NLP state, Allowned:false, Enabled:false
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1304): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.plus (4007/10160)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.plus (4007/10160)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/ProviderInstaller( 4633): Installed default security provider GmsCore_OpenSSL
W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/CheckinService( 2151): Checkin interval check for package: unspecified last checkin: 1450742971750 min interval config: 0 actual interval: 53263
D/PMS     (  984): acquireWL(43b3c970): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/PMS     (  984): releaseWL(43b3c970): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4007): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2151, uid=10029, userID:0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
,W/dalvikvm( 4633): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4633): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4633): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4633): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,E/MDM     ( 1225): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/WVCdm   (  364): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  364): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  364): CdmEngine::OpenSession
,I/WVCdm   (  364): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  364): CdmEngine::GenerateKeyRequest
,D/AuthorizationBluetoothService( 1363): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1363): Proximity feature is not enabled.
,D/LocationInitializer( 2151): Restart initialization of location
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4633): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  984): acquireWL(435ab900): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(435ab900): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/WVCdm   (  364): PrepareKeyRequest: nonce=2114346829
,I/WVCdm   (  364): CdmEngine::CloseSession
,W/dalvikvm( 4407): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4407): threadid=1: thread exiting with uncaught exception (group=0x41de4e30)
,E/ActivityManager(  984): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4407): FATAL EXCEPTION: main
E/AndroidRuntime( 4407): Process: com.test.thalitest, PID: 4407
E/AndroidRuntime( 4407): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4407): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4407): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4407): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4407): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4407): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4407): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4407): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4407): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4407): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4407): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4407): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  984):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  984): killProcessQuiet, pid=4276
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,D/Process ( 4407): killProcess, pid=4407
,D/Process ( 4407): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  984): Killing 4276:com.htc.backup/1000 (adj 15): empty #17
,I/WVCdm   (  364): CdmEngine::OpenSession
,I/WVCdm   (  364): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  364): CdmEngine::GenerateKeyRequest
,I/ActivityManager(  984): Recipient 4407
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  984): WIN DEATH: Window{43644210 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  984): Client connection lost with reason: 4
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  984): Process com.test.thalitest (pid 4407) has died.
,I/ActivityManager(  984): Recipient 4276
,D/WVCdm   (  364): PrepareKeyRequest: nonce=3884560018
,I/WVCdm   (  364): CdmEngine::CloseSession
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (4633/10029)
W/InputMethodManagerService(  984): Got RemoteException sending setActive(false) notification to pid 4407 uid 10389
,W/Binder  ( 1211): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1211): java.lang.NullPointerException
W/Binder  ( 1211): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1211): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1211): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1211): 	at dalvik.system.NativeStart.run(Native Method)
,I/Adreno-EGL( 4633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4633): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4633): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4633): Local Branch: 
I/Adreno-EGL( 4633): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4633): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4633):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4633): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4633): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4633): Local Branch: 
I/Adreno-EGL( 4633): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4633): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4633):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4633): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4633): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4633): Local Branch: 
I/Adreno-EGL( 4633): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4633): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4633):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4633): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2151): Classify the device as Phone.
,D/libc    ( 2151): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2151): [NET] getaddrinfo-,err=8
D/libc    ( 2151): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2151): [NET] getaddrinfo-, 1
,D/libc    ( 2151): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =9b8d +++++,
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE,
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 258
,D/libc    (  357): [NET]res_nsend:resplen=84
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2151): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 2151): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2151): [NET] getaddrinfo-,err=8
,D/libc    ( 2151): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2151): [NET] getaddrinfo-,err=8
,D/libc    ( 2151): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2151): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2151): Sending checkin request (12201 bytes)
,D/libc    (  984): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  984): [NET] getaddrinfo-,err=8
D/libc    (  984): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  984): [NET] getaddrinfo-, 1
,D/libc    (  984): [NET] getaddrinfo_proxy+
,D/libc    (  357): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  357): [NET] +++++ res_nsend xid =7349 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE,
,I/CheckinRequestBuilder( 2151): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  984): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2151): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  357): [NET]res_nsend:resplen=172
D/libc    (  357): [NET]res_queryN: exit 3, ancount=4
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  984): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  984): Find DNS Address www.htc.com/104.81.130.175
,D/ConnectivityService(  984): getNetworkInfo networkType=9 called by com.google.android.gms (2151/10029)
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=15 [20][3][0]
,I/CheckinRequestBuilder( 2151): Classify the device as Phone.
,I/CheckinTask( 2151): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2151): Checking schedule, now: 1450743027032 next: 1451265964028
,I/CheckinService( 2151): active receiver: disabled
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2151, uid=10029, userID:0
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,I/CheckinService( 2151): Checking schedule, now: 1450743027063 next: 1451265964028
,I/CheckinService( 2151): active receiver: disabled
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2151, uid=10029, userID:0
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
,D/CheckinService( 2151): Recording last checkin time for package unspecified as 1450743027071
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(4333a8f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2151/10029)
,D/PMS     (  984): acquireWL(440e5730): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1363): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1363): [NET] getaddrinfo-,err=8
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1363): [NET] getaddrinfo-, 1
,D/libc    ( 1363): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =97e0 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 234
D/libc    (  357): [NET]res_nsend:resplen=79
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1363): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=14 [7][1][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  984): acquireWL(44012838): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  984): releaseWL(440e5730): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  984): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  984): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/PMS     (  984): releaseWL(44012838): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(43dd4720): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
,D/ConnectivityService(  984): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  984): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
,D/ConnectivityService(  984): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(43dd4720): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4523): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027),
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/PMS     (  984): releaseWL(43dd45a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  984): acquireWL(4390fce0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4503 10154 null
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4503, uid=10154, userID:0
,I/MusicLeanback( 4503): Conditions not met for autocaching.
,I/MusicLeanback( 4503): Stop autocaching.
D/PMS     (  984): releaseWL(4390fce0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  984): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  984): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/WifiStateMachine(  984): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  984): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4603): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  984): killProcessQuiet, pid=4300
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 4300:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 4300
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  984): killProcessQuiet, pid=3884
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 3884:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 3884
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1340): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  984): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4704 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "sms"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
,W/Prism.AllAppsManager( 1269): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "smsto"
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1340): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1340): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "mms"
I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsUpdated
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "mmsto"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "sms"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1340): Unsupported attribute readOnly
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "smsto"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "mms"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "mmsto"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4704): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4704): MmsConfig.loadMmsSettings
,W/dalvikvm( 4704): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4704): VFY: unable to resolve instance field 36
,W/dalvikvm( 4704): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4704): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  984): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4727 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  984): Waited long enough for: ServiceRecord{435b2a18 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4704, uid=10111, userID:0
,W/Settings( 4704): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4727): onCreate
,D/CaptivePortalTracker(  984): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  984): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/MmsCustomizationProvider( 4727): query uri: content://htc-mms-customization/mms-ua/ua_string
V/GetPrviateResource( 4727): GetPrviateResource
,V/GetPrviateResource( 4727): GetPrviateResource
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4704, uid=10111, userID:0
D/ConnectivityService(  984): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4704, uid=10111, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4704, uid=10111, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4704, uid=10111, userID:0
,D/MmsCustomizationProvider( 4727): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4704, uid=10111, userID:0
D/PMS     (  984): acquireWL(43e81e90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4704 10111 null
I/Babel   ( 4704): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4704): MmsConfig.loadFromDatabase
E/Babel   ( 4704): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4704): MmsConfig.loadFromResources
E/Babel   ( 4704): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4704): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/PackageManager(  984): Unable to load service info ResolveInfo{4362ef88 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  984): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  984): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  984): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  984): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  984): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  984): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  984): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  984): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  984): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  984): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  984): acquireWL(440c5610): PARTIAL_WAKE_LOCK  AsyncService 0x1 4007 10160 null
I/ActivityManager(  984): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  984): acquireWL(4388df40): PARTIAL_WAKE_LOCK  Icing 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4704): Installed default security provider GmsCore_OpenSSL
D/PMS     (  984): releaseWL(4388df40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 4007): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/MessageCustFlag( 4727): sense_version=6.0
D/BTAccessoryUtil( 4727): createReceiver
D/PMS     (  984): acquireWL(43491e08): PARTIAL_WAKE_LOCK  Icing 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(440c5610): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  984): releaseWL(43e81e90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/dalvikvm-heap( 4007): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
D/BTAccessoryUtil( 4727): registerReceiver return intent = null
D/MessageCustFlag( 4727): sku_id=99
W/SystemReader( 4727): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  984): Resuming delayed broadcast
D/Messaging( 4727): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4727): networkCode: 
D/MessageCustFlag( 4727): sku_id=99
D/MmsConfig( 4727): SIE smsPri: null
D/MmsConfig( 4727): networkCode: 
D/HtcTelephonyCapability( 4727): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4727): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4727): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4727): Cannot find qct_8960_interface, use default value instead
,D/Process (  984): killProcessQuiet, pid=4247
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  984): Killing 4247:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/PackageBroadcastService( 2151): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2151): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  984): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  984): Recipient 4247
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  984): Resuming delayed broadcast
,I/Icing   ( 2151): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  984): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  984): start
,I/GCoreNlp( 1225): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  984): applying state to connected service,
D/PMS     (  984): acquireWL(448d7368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(448d7368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  984): applying state to connected service
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
D/PMS     (  984): acquireWL(447db9a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(447db9a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(447d9ce0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(447d9ce0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(447a90f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(447a90f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 664 ms] updated apps [took 664 ms] 
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@422a7c78 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,I/Icing   ( 2151): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2151): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@422a7c78 -
,D/PMS     (  984): releaseWL(43491e08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/Messaging( 4727): mNeedToUpdateDate2 start
,D/MmsConfig( 4727): packageName: com.htc.vvm.att does not exist
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/ReportIndicatorCache( 4727): startAsyncQueryReports ---
,D/MmsSmsV2Provider( 1243):  phoneType = -1
D/SettingsManager( 4727): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@422233b8
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsAsyncWorkHandler( 4727): 
D/MmsAsyncWorkHandler( 4727): HM tk = 20001
D/ReportIndicatorCache( 4727): MSG_QUERY_REPORTS >>
,I/Messaging( 4727): mccmnc> 
,D/DraftCache( 4727): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4727): [DraftCache/1] refresh
,D/MmsConfig( 4727): networkCode: 
,D/Messaging( 4727): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/PhoneStorageUtil( 4727): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4727): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4727): createReceiver
,D/MessageCustFlag( 4727): sense_version=6.0
,D/Jerry   ( 4727): start to preload cursor >>>>>>>
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): sku_id=99
,D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1243): Update uri=content://mms, match=0
,V/MmsProvider( 1243): selection=st=129 AND m_type!=134
,D/Messaging( 4727): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4727): TransactionService is going to be woken up.
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1243):  phoneType = -1
D/DraftCache( 4727): [DraftCache/469] rebuildCache
,V/TransactionService( 4727): 1-Creating TransactionService
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
V/TransactionService( 4727): onStartCommand: 1
,D/MmsSystemEventReceiver( 4727): unRegisterForConnectionStateChanges
V/TransactionService( 4727): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4727): Loading previous transactions.
,D/Messaging( 4727): mNeedToUpdateDate2: false
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4727): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): device_type: 1
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
,D/Jerry   ( 1243): URI_DRAFT
,D/TransactionService( 4727): Force set service start id to 1
V/TransactionService( 4727): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4727): unRegisterForConnectionStateChanges
V/TransactionService( 4727): Destroying TransactionService
,D/TransactionService( 4727): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4727): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/DraftCache( 4727): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4727): [DraftCache/469] rebuildCache time: 1
,D/MmsAsyncWorkHandler( 4727): 
D/MmsAsyncWorkHandler( 4727): HM tk = 20002
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1243): sku_id=99
D/Messaging( 4727): ViewCache CreatePreload
,D/Messaging( 4727): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4727): _has_set_default_values_2=true
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): sku_id=99
,D/MsgPreferenceUtils( 4727): def_index: 0
,D/MsgPreferenceUtils( 4727): globalIndex = 1
D/MsgPreferenceUtils( 4727): phone state: true
D/MsgPreferenceUtils( 4727): sd state: false
,D/MsgPreferenceUtils( 4727): vIndex = 0
,D/PMS     (  984): acquireWL(43644438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  984): sending alarm PendingIntent{42659958: PendingIntentRecord{42ddc680 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=127220, Int=0
,D/PMS     (  984): acquireWL(43826248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(43644438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [9][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  984): acquireWL(440e5240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(43826248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(440e5240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(42d49880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(42d49880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(42abfc50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  984): acquireWL(42c46d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4704): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  984): acquireWL(4292c0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1225): Vacuum at: now=1450743040028 tag=VacuumService
D/PMS     (  984): releaseWL(42abfc50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(42c46d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(434f7c58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): releaseWL(4292c0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  984): releaseWL(434f7c58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): acquireWL(430b9120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
D/PMS     (  984): releaseWL(430b9120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): acquireWL(43a91430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(43a91430): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(443a9880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): releaseWL(443a9880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): acquireWL(42ca4e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  984): acquireWL(43ff8cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(43ff8cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(42d06b18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(42ca4e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(42b0f0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(42b0f0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1225): Scheduling Phenotype for one-off execution 617 seconds from now (1450743040586)
,D/GetConfigurationSnapshotOperation( 1225): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1225): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1225): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  984): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
,D/libc    (  357): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =3df +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  357): [NET]res_nsend:resplen=87
D/libc    (  357): [NET]res_queryN: exit 3, ancount=2
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  984): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  984): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  984): releaseWL(42d06b18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(42dc29c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(42dc29c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(43611628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(43611628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(438b1868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PMS     (  984): releaseWL(438b1868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  984): acquireWL(44296ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  984): sending alarm PendingIntent{4493eed0: PendingIntentRecord{42d1f0a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138204, Int=0
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  984): releaseWL(44296ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1304): service - mHandler: update timezone
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  984): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1525): service - onCreate()
W/ActivityManager(  984): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1525): service - mHandler: update timezone
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  984): batLight: Full, plugged
V/LightsService(  984): setLight #8: color=#c8c800
D/qdlights(  984): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  984): setLight #8: color=#c800
D/qdlights(  984): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute
D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1525): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1525): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{42368170 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1304): service - mHandler: update timezone
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  984): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1525): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
V/NotificationService(  984): batLight: Full, plugged
V/LightsService(  984): setLight #8: color=#c8c800
D/qdlights(  984): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  984): setLight #8: color=#c800
D/qdlights(  984): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  984): [LedInfo] has indicator attribute
D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  984): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ActivityManager(  984): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1525): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1525): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1525): service - mHandler: update timezone
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1525): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1525): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1525): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{425b2ca0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/AutoSetting( 1304): service - handleMessage() stop self
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 4 7 2 11
,D/AutoSetting( 1304): service - handleMessage() quit looper
,D/AutoSetting( 1304): service - onDestroy() END
,D/GpsLocationProvider(  984): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  984): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  984): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  984): acquireWL(42d1acd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
V/AlarmManager(  984): sending alarm PendingIntent{42ba6690: PendingIntentRecord{42a705a8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143391, Int=0
D/PMS     (  984): acquireWL(42e71370): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 984 1000 null
D/PMS     (  984): releaseWL(42d1acd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  984): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  984): [NET] getaddrinfo-,err=8
D/libc    (  984): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  984): [NET] getaddrinfo-, 1
,D/libc    (  984): [NET] getaddrinfo_proxy+
D/libc    (  357): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  357): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  357): [NET] +++++ res_nsend xid =7f50 +++++
D/libc    (  357): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  357): [NET] NOT IN CACHE
,D/libc    (  357): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  357): [NET]res_nsend:resplen=238
D/libc    (  357): [NET]res_queryN: exit 3, ancount=10
D/libc    (  357): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  357): [NET] getaddrinfo-, SUCCESS
D/libc    (  984): [NET] getaddrinfo_proxy-, success
I/global  (  984): call createSocket() return a new socket.
D/libc    (  984): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  984): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  984): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  984): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  984): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  984):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  984): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  984): acquireWL(43da1f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(43da1f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  984): releaseWL(42e71370): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  984): killProcessQuiet, pid=4333
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 4333:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 4333
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  984): Waited long enough for: ServiceRecord{4476d140 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  984): acquireWL(44795ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(44795ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1525): service - handleMessage() stop self
,D/AutoSetting( 1525): service - onDestroy() END
,D/AutoSetting( 1525): service - handleMessage() quit looper
,D/Process (  984): killProcessQuiet, pid=4348
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 4348:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 4348
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  984): acquireWL(43364bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{10027}
,V/AlarmManager(  984): sending alarm PendingIntent{44076fc0: PendingIntentRecord{43d4c820 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=175865, Int=0
,D/PMS     (  984): releaseWL(43364bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  984): acquireWL(42a83868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  984): releaseWL(42a83868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  984): acquireWL(439d09d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(439d09d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42dbee38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-,
I/BatteryService(  984): n_update end
D/HtcPowerSaver(  984): updateBatteryInfo
,D/PMS     (  984): releaseWL(42dbee38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  984): acquireWL(4422a758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(4422a758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  984): acquireWL(42dd7090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=267403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(42dd7090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  984): acquireWL(43de8870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(43de8870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  984): acquireWL(44230d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PMS     (  984): releaseWL(44230d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(443bf918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=327404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(443bf918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  984): acquireWL(434fc528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PMS     (  984): releaseWL(434fc528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  984): acquireWL(4483d120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=387403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(4483d120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  984): acquireWL(435b2798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(435b2798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  984): acquireWL(43b1db30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(43b1db30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/HtcPowerSaver(  984): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(440e49f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=447403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(440e49f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  984): acquireWL(440f6f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(440f6f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  984): acquireWL(43f5afc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(43f5afc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  984): acquireWL(44087a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=507404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(44087a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  984): acquireWL(433b80b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
,D/PMS     (  984): releaseWL(433b80b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  984): acquireWL(43a66650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PMS     (  984): releaseWL(43a66650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/HtcPowerSaver(  984): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(42cd2500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=567404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(42cd2500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(43a62890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(43a62890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/HtcPowerSaver(  984): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(433dba50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PMS     (  984): releaseWL(433dba50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  984): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1243): sku_id=99
D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  984): acquireWL(43fe9ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=627404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(43fe9ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  984): killProcessQuiet, pid=4077
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 4077:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  984): Recipient 4077
,D/PMS     (  984): acquireWL(43f4f450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(43f4f450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(440d4eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
D/UsbnetService(  984): BroadcastReceiver::onReceive+
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1119): closing low battery warning: level=100
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PMS     (  984): releaseWL(440d4eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(433cd918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=687403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1269): Grow heap (frag case) to 12.658MB for 50416-byte allocation
D/PMS     (  984): releaseWL(433cd918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(441fcd28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
,D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  984): releaseWL(441fcd28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  984): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(43810ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PMS     (  984): releaseWL(43810ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(434daac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=747403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(434daac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(440f8158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
,D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  984): releaseWL(440f8158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(44791df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(44791df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(42debfb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=807403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(42debfb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42d9eb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(42d9eb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
,D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(438b0b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=867404, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(438b0b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(4385f188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(4385f188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(42da2f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=927403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1269): Grow heap (frag case) to 12.659MB for 50416-byte allocation
D/PMS     (  984): releaseWL(42da2f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42f84e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42f84e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(433d6d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PMS     (  984): releaseWL(433d6d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(4424a380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=987404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(4424a380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(44371f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,D/ConnectivityService(  984): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  984): Done.
D/ConnectivityService(  984): Setting timer for 720seconds
,V/AlarmManager(  984): sending alarm PendingIntent{424b4d28: PendingIntentRecord{42ba6a30 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787389, Int=0
,I/ActivityManager(  984): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4840 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  984): sending alarm PendingIntent{429916d0: PendingIntentRecord{429a2b50 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450743125381, Int=10800000
,V/AlarmManager(  984): sending alarm PendingIntent{42c72aa0: PendingIntentRecord{42ab3308 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450743845744, Int=900000
,V/AlarmManager(  984): sending alarm PendingIntent{42c46ed8: PendingIntentRecord{42c399f8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450743920088, Int=0
,W/ContextImpl( 4463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4463): call getInstance()
,D/SmartSyncUtils( 4463): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4463): MY_DEBUG = false
D/PMS     (  984): releaseWL(44371f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  984): acquireWL(43e144b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4463 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4463): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4463): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4463): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4463): SettingOnTime = 1450764000000, randomSettingOnTime = 1450761710000
,D/SmartSyncScreenOnOffTimeReceiver( 4463): SettingOffTime = 1450749600000, randomSettingOffTime = 1450750834000
,D/SmartSyncScreenOnOffTimeReceiver( 4463): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4463): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4463): bNightModeTurnOffOnce = false
D/PMS     (  984): releaseWL(43e144b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  984): Couldn't get kernel wake lock stats
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.aurora (4840/10049)
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,W/BatSI   (  984): Couldn't get kernel wake lock stats
,W/BatSI   (  984): Couldn't get kernel wake lock stats
,W/BatSI   (  984): Couldn't get kernel wake lock stats
,D/Process (  984): killProcessQuiet, pid=4378
,I/ActivityManager(  984): Killing 4378:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  984): Recipient 4378
,D/PMS     (  984): acquireWL(42b65050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42b65050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  984): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/HtcPowerSaver(  984): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(42d9fe78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  984): sending alarm PendingIntent{442c7e40: PendingIntentRecord{42e2d250 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1014829, Int=0
,D/PMS     (  984): acquireWL(42993ab0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(42993ab0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(42d9fe78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(4253ad40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  984): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  984): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  984): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (1363/10029)
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
,D/PMS     (  984): releaseWL(4253ad40): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  984): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  984): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=3 [116][4][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  984): acquireWL(434dff08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(434dff08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(435a75a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1047404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(435a75a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42c067a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42c067a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/HtcPowerSaver(  984): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(424857d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(424857d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(434e2360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1107404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(434e2360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42cf49b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42cf49b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  984): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(43b42f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1167403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(43b42f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(43ea02b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(43ea02b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  984): acquireWL(44380880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1227403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(44380880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42c9d5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42c9d5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(43a69bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(43a69bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/HtcPowerSaver(  984): >> updateStatus
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(449370f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1287403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(449370f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(4343b7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(4343b7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(439a4a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(439a4a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(442ccd18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1347403, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(442ccd18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(43b382e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
I/BatteryService(  984): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  984): releaseWL(43b382e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(443f14b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(443f14b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  984): updateBatteryInfo
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
,I/HtcPowerSaver(  984): >> updateStatus
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(42ace8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1407404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(42ace8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(438376a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(438376a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(43810fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(43810fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(447da708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1467404, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(447da708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(43632418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  984): n_update end
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): releaseWL(43632418): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(438ac290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(438ac290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(42da6120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1527403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(42da6120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42cbf6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42cbf6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(42e1b8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42e1b8d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(438b1e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1587403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(438b1e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42ca3af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42ca3af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(433392c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
D/PMS     (  984): releaseWL(433392c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(434de1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1647403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(434de1d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(4421a448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(4421a448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(42e6cda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1707403, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(42e6cda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(44793a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(44793a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(42f142b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42f142b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  984): acquireWL(43df1938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1767403, Int=0
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(43df1938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  984): Couldn't get kernel wake lock stats
,D/PMS     (  984): acquireWL(447a7fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  984): n_update end
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
,D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  984): releaseWL(447a7fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  984): acquireWL(447806c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1827404, Int=0
,I/ProcessStatsService(  984): Prepared write state in 49ms
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  984): Pruning old procstats: /data/system/procstats/state-2015-12-21-05-05-00.bin
,D/PMS     (  984): releaseWL(447806c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(43b3b628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  984): releaseWL(43b3b628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  984): Sampling interval elapsed, updating statistics ..
D/PMS     (  984): acquireWL(4392a828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
V/AlarmManager(  984): sending alarm PendingIntent{424b4d28: PendingIntentRecord{42ba6a30 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1727529, Int=0
V/AlarmManager(  984): sending alarm PendingIntent{426830d0: PendingIntentRecord{42ce7e18 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1822776, Int=1800000
,V/AlarmManager(  984): sending alarm PendingIntent{42bb4348: PendingIntentRecord{42c5c1b8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1850321, Int=0
,V/AlarmManager(  984): sending alarm PendingIntent{424770a0: PendingIntentRecord{42c0cfb8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1863406, Int=0
,V/AlarmManager(  984): sending alarm PendingIntent{43ea8a50: PendingIntentRecord{42ded5d0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450744343823, Int=1800000
,V/AlarmManager(  984): sending alarm PendingIntent{42c72aa0: PendingIntentRecord{42ab3308 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450744745744, Int=900000
,D/ConnectivityService(  984): Done.
D/PMS     (  984): acquireWL(43e9c128): PARTIAL_WAKE_LOCK  NetworkStats 0x1 984 1000 null
,D/ConnectivityService(  984): Setting timer for 720seconds
,D/PMS     (  984): releaseWL(43e9c128): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  984): acquireWL(44769e40): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 984 1000 null
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/LocationManagerService(  984): getAllProviders()=[passive, gps, network]
D/PMS     (  984): acquireWL(44051ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): acquireWL(42dfd560): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): acquireWL(440e3f80): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(42dfd560): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4463): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  984): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,I/EventLogService( 2151): Aggregate from 1450743024590 (log), 1450742543781 (data)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=10 [58][6][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/BatSI   (  984): Couldn't get kernel wake lock stats
D/PMS     (  984): acquireWL(4438ee28): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 984 1000 WorkSource{10160}
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  984): acquireWL(438b2218): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 984 1000 WorkSource{10029}
D/PMS     (  984): releaseWL(44769e40): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  984): releaseWL(44051ea0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(44786f20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  984): releaseWL(44786f20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(441fd2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(441fd2f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(447a79c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(447a79c8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/BatSI   (  984): Couldn't get kernel wake lock stats
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025325
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025731
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025830
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025842
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025846
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360025852
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027254
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360027268
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029934
I/ActivityManager(  984): Resuming delayed broadcast
,D/PMS     (  984): releaseWL(4392a828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): releaseWL(440e3f80): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(434e6da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(4438ee28): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  984): releaseWL(434e6da0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315361863712
,W/AlarmManager(  984): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{422b2ec0: PendingIntentRecord{432001c0 com.google.android.gms startService}}) : type=2 triggerAtTime=315361863712 win=-1 tElapsed=315361863712 maxElapsed=551881863710 interval=0 standalone=false
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(4488e010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(438b2218): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  984): releaseWL(4488e010): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/BatSI   (  984): Couldn't get kernel wake lock stats
,W/BatSI   (  984): Couldn't get kernel wake lock stats
,D/PMS     (  984): acquireWL(423dd410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/UsbnetService(  984): BroadcastReceiver::onReceive+
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  984): releaseWL(423dd410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  984): updateBatteryInfo
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  984): acquireWL(42b1ce10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,V/AlarmManager(  984): sending alarm PendingIntent{42252600: PendingIntentRecord{423de168 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1887403, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  984): releaseWL(42b1ce10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): acquireWL(42abb8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 984 1000 WorkSource{1000}
,D/PMS     (  984): acquireWL(42a98a78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 984 1000 null
,V/AlarmManager(  984): sending alarm PendingIntent{424770a0: PendingIntentRecord{42c0cfb8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1893548, Int=0
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(42a3d0b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(42abb8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  984): releaseWL(42a98a78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  984): releaseWL(42a3d0b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  984): acquireWL(42c7eac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  984): n_update end
,D/PMS     (  984): releaseWL(42c7eac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  984): updateBatteryInfo,
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  984): BroadcastReceiver::onReceive+
D/UsbnetService(  984): onReceive BATTERY_CHANGED
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  984):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  984): BroadcastReceiver::onReceive-
D/PMS     (  984): runPSCheck
D/HtcPowerSaver(  984): Checking...
I/HtcPowerSaver(  984): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  984): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  984): << updateStatus
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4895): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4895): ====startRecUseTime====
D/htc.customization.log.level( 4895):  is 
W/CustomizationLogLevel( 4895): Level value is invalid, use default level 2
D/CustomizationManager( 4895):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4895): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4895): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4895): Parsing tag category name = system
I/CustomizationCIDLoader( 4895): Parsing tag category name = application
I/CustomizationCIDLoader( 4895): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4895): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4895): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4895): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4895): Parsing tag category name = Settings
D/CustomizationManager( 4895):  Read CID file spent 0.161 (s)
D/CustomizationManager( 4895):  All configurations done spent 0.161 (s)
W/HtcNativeFlag( 4895): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4895): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4895): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4895): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  984): deletePackageAsUser: pkg=com.test.thalitest, pid=4895, uid=2000 user=0
I/ActivityManager(  984): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  984): killProcessQuiet, pid=4603
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  984): killProcessQuiet, pid=4588
I/ActivityManager(  984): Killing 4603:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  984): Killing 4588:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  984): killProcessQuiet, pid=4574
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  984): Killing 4574:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  984): Recipient 4588
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Recipient 4574
W/asset   (  984): Copying FileAsset 0x6d13ea20 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  984): Skipping PackageSetting{42927f90 com.example.hello/10397} due to missing metadata
I/ActivityManager(  984): Recipient 4603
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/PMS     (  984): acquireWL(44879d60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1340): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/VoicemailCleanupService( 1289): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  984): releaseWL(44879d60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "sms"
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  984):   Scheme: "smsto"
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "mms"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/InputMethodManagerService(  984): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "mmsto"
W/AccTypeManager( 1340): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1340): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/IcingCorporaProvider( 2830): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "sms"
I/ActivityManager(  984): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4910 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1340): Unsupported attribute readOnly
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "smsto"
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "mms"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "mmsto"
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  984): acquireWL(440cdc48): PARTIAL_WAKE_LOCK  Icing 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(440cdc48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): acquireWL(44080e58): PARTIAL_WAKE_LOCK  Icing 0x1 2151 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2830): UpdateCorporaTask done [took 355 ms] updated apps [took 355 ms] 
W/PackageManager(  984): Unable to load service info ResolveInfo{42b25798 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  984): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  984): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  984): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  984): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  984): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  984): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  984): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  984): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  984): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  984): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4910): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4910): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4910): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4910): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4910): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4910): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4910): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4910): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4910): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4910): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4910): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4910): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4910): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4910): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4910): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4910): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4910): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4910): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4910): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4910): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4910): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4910): Opened ClientFlag.db in read-only mode
D/Process (  984): killProcessQuiet, pid=4503
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
I/ActivityManager(  984): Killing 4503:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  984): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4929 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (4910/10100)
W/GAV2    ( 4910): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (4910/10100)
D/RemoteDisplayProvider(  984): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  984): start
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Recipient 4503
D/MediaRouterService(  984): Client com.google.android.music (pid 4503): Died!
W/AtomicFile(  984): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  984): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  984): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4929): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4929): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4929): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4929): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4929): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4929): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4929): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4929): threadid=10: thread exiting with uncaught exception (group=0x41de4e30)
E/ActivityManager(  984): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4929): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4929): Process: com.android.keychain, PID: 4929
E/AndroidRuntime( 4929): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4929): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4929): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4929): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4929): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4929): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4929): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4929): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4929): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4929): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  984): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4929): killProcess, pid=4929
D/Process ( 4929): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  984): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  984): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450744828194.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  984): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  984): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  984): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  984): 	... 4 more
I/ActivityManager(  984): Recipient 4929
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Process com.android.keychain (pid 4929) has died.
W/ActivityManager(  984): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4950 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4950): getInstance(Context context)
D/AppTag  ( 4950): getInstance(Context context)
D/AppTag  ( 4950): onCreate()
I/ActivityManager(  984): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
W/GAV2    ( 4910): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  984): Resuming delayed broadcast
D/PMS     (  984): acquireWL(43e0f090): PARTIAL_WAKE_LOCK  AsyncService 0x1 4007 10160 null
D/PMS     (  984): releaseWL(43e0f090): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4030): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2151): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2151): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2151): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2151): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2151): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2151): Module APK com.google.android.play.games already loaded
I/ActivityManager(  984): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2151): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2151): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e565218
W/dalvikvm( 2151): threadid=44: thread exiting with uncaught exception (group=0x41de4e30)
E/SQLiteLog( 2151): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2151): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb24168
I/LocationSettingsChecker( 2151): Removing dialog suppression flag for package com.test.thalitest
E/DriveAsyncService( 2151): disk I/O error (code 3850)
E/DriveAsyncService( 2151): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2151): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2151): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2151): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2151): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2151): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2151): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2151): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2151): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2151): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2151): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2151): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2151): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2151): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2151): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2151): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  984): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2151): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2151): Process: com.google.android.gms, PID: 2151
E/AndroidRuntime( 2151): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2151): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2151): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2151): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2151): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2151): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2151): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2151): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2151): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2151): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2151): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2151): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2151): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2151): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2151): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2151): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2151): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2151): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2151): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 2151): killProcess, pid=2151
D/Process ( 2151): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  984): Can't write: system_app_crash
E/DropBoxManagerService(  984): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  984): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  984): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  984): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  984): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  984): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  984): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  984): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  984): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  984): 	... 5 more
D/WifiService(  984): Client connection lost with reason: 4
D/PMS     (  984): handleWLDeath(44080e58): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  984): Recipient 2151
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Process com.google.android.gms (pid 2151) has died.
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10999ms
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
I/ActivityManager(  984): Resuming delayed broadcast
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10997ms
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20997ms
E/SQLiteLog( 1363): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1363): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x64070060
W/dalvikvm( 1363): threadid=1: thread exiting with uncaught exception (group=0x41de4e30)
E/ActivityManager(  984): App crashed! Process: com.google.process.gapps
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
E/DropBoxManagerService(  984): Can't write: system_app_crash
E/DropBoxManagerService(  984): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  984): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  984): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  984): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  984): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  984): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  984): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  984): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  984): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  984): 	... 5 more
D/Process ( 1363): killProcess, pid=1363
D/Process ( 1363): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  984): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4979 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4979): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4979 dbg=false s=true
I/DeviceManagement( 4979): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4979): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4979): WorkflowService: Starting workflow service
I/DeviceManagement( 4979): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42243068] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4979): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4979): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4979): PackageUpdateWorkflow: ==================================================
I/ActivityManager(  984): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 4979): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 4979): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4979): SessionStateController: Checking invariants...
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@422a7c78 +
I/Prism.WidgetManager( 1269): onLoadItems() +
I/ActivityManager(  984): Recipient 1363
I/ActivityManager(  984): Process com.google.process.gapps (pid 1363) has died.
W/ActivityManager(  984): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30818ms
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  984): Client connection lost with reason: 4
E/SQLiteDatabase( 4979): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4979): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4979): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4979): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4979): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4979): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4979): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4979): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4979): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4979): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4979): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4979): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 4979): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4979): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4979): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4979): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4979): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4979): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4979): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4979): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4979): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4979): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@42243068]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4979): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4979): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4979): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4979): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4979): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4979): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4979): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4979): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4979): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4979): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4979): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4979): WorkflowService: Stopping workflow service
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4995 uid=10099 gids={50099, 3003, 5012}
D/Documents( 4995): Loading roots for com.android.providers.downloads.documents
D/Documents( 4995): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4995): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4995): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4995): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4995): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4995): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4995): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4995): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4995): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4995): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4995): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4995): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4995): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4995): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4995): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4995): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4995): threadid=1: thread exiting with uncaught exception (group=0x41de4e30)
E/AndroidRuntime( 4995): FATAL EXCEPTION: main
E/AndroidRuntime( 4995): Process: com.android.documentsui, PID: 4995
E/AndroidRuntime( 4995): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4995): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4995): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4995): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4995): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4995): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4995): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4995): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4995): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4995): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4995): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4995): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4995): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4995): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4995): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4995): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4995): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4995): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4995): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4995): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4995): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4995): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4995): 	... 10 more
I/ActivityManager(  984): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5008 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  984): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5020 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ActivityManager(  984): App crashed! Process: com.android.documentsui
D/ErrorReport(  984): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4995): killProcess, pid=4995
D/Process ( 4995): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  984): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  984): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450744829054.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  984): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  984): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  984): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  984): 	... 4 more

```
