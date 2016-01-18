#### Test 5615109370bee58_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
,E/cutils-trace( 4401): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4401): ====startRecUseTime====
D/htc.customization.log.level( 4401):  is 
W/CustomizationLogLevel( 4401): Level value is invalid, use default level 2
D/CustomizationManager( 4401):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4401): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4401): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4401): Parsing tag category name = system
I/CustomizationCIDLoader( 4401): Parsing tag category name = application
I/CustomizationCIDLoader( 4401): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4401): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4401): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4401): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4401): Parsing tag category name = Settings
D/CustomizationManager( 4401):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4401):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4401): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4401): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4401): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4401): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4401
D/PMS     (  903): acquireHCC(43544c68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(43805250): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
W/asset   (  903): Copying FileAsset 0x6cd6b240 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1127722224
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
D/PMS     (  903): acquireWL(443b75e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bc8c30
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4412 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4412): Copying FileAsset 0x5c869428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4412): Binding Chromium to main looper Looper (main, tid 1) {41b1db78}
I/LibraryLoader( 4412): Expected native library version number "",actual native library version number ""
I/chromium( 4412): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4412): Initializing chromium process, renderers=0
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e2e268:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4412): 1102265896: getState(). Returning 12
D/PMS     (  903): acquireWL(44658518): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): acquireWL(443d02a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): releaseWL(44658518): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4412): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4412): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4412): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4412): Local Branch: 
I/Adreno-EGL( 4412): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4412): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4412):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4412): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4412): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4412): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4412): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4412): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4412): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4412): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4412): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4412): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4412): CordovaWebView is running on device made by: HTC
,W/AwContents( 4412): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1271
,W/ResourceType( 4412): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4412): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b654d8, mServedView=org.apache.cordova.engine.SystemWebView{41b2b140 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  903): Enable input method client, pid=4412
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4412): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +387ms
,D/PMS     (  903): releaseWL(443b75e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4412): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4412): JniHelper::setJavaVM(0x415f8048), pthread_self() = 1663700944
,D/JX-Cordova( 4412): jxcore cordova android initializing
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 11.993MB for 42652-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 12.075MB for 95956-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 12.149MB for 143930-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 12.264MB for 215890-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 12.439MB for 323830-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 13.679MB for 1092904-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 14.630MB for 1639352-byte allocation
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 15.880MB for 2459024-byte allocation
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
D/PMS     (  903): releaseHCC(43544c68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(43805250): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4412): Grow heap (frag case) to 18.064MB for 3688532-byte allocation
,W/jxcore-log( 4412): Initializing JXcore engine
,W/jxcore-log( 4412): JXcore engine is ready
,W/jxcore-log( 4412): Starting JXcore engine
,W/jxcore-log( 4412): Platform android
W/jxcore-log( 4412): 
,W/jxcore-log( 4412): Process ARCH arm
W/jxcore-log( 4412): 
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4218c9e0
,W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
,V/LightsService(  903): setLight #0: color=#0
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4218c9e0, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423bc450
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@42763be0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  903): mWirelessDisplayManager is null
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 318ms
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43d91460)
,D/NfcService( 1255): applyRouting -2
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
I/InputMethodManagerService(  903): Disable input method client, pid=4412
D/PMN     (  903): wakingUp
D/PMS     (  903): acquireWL(4436ebf0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  903): releaseWL(4436ebf0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  903): No lock screen! windowToken=null
,D/PMN     (  903): onScreenOn
,I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
,D/PMS     (  903): acquireWL(43aacbb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/MtpService( 2680): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2680): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/NfcService( 1255): applyRouting -2
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  903): releaseWL(43aacbb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): acquireWL(423a8138): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
,D/PMS     (  903): releaseWL(423a8138): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1318): receiver - intent: android.intent.action.USER_PRESENT
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 4052): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4052): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4052): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4052): Cust_ConnectToPC   : spcsc>false
D/        ( 4052): Cust_ConnectToPC   : IPT>true
D/        ( 4052): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4052): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4052): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4052): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4052): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/PSReceiver( 4052): onReceive:android.intent.action.USER_PRESENT
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19975 delay=15s
,I/SmartNS_PSService( 4052): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4052): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4052):  defaultType:0
W/ContextImpl( 4052): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:On
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  903): updateScreenOn: false
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4195): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4195): isEpsOn(), nState = 0
,D/PMS     (  903): acquireWL(4235b720): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4195 1000 null
I/ClockThread( 1114): stop update clock
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): releaseWL(443d02a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  903): releaseWL(4235b720): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  903): acquireWL(426445e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(426445e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4195): getMobilePolicyEnabled, result = true
D/PMS     (  903): acquireWL(42362dc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(42362dc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOn: 1453126576896
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOn: 1453126576896
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423bc450
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@423bc450, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@42763be0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/jxcore-log( 4412): JXcore Cordova bridge is ready!
I/jxcore-log( 4412): 
,W/jxcore-log( 4412): JXcore engine is started
,I/chromium( 4412): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/ResourceType( 4412): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4412): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b2b140 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(424e5ca8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19975 mDataStallAlarmIntent=PendingIntent{426b21e8: PendingIntentRecord{4248b328 android broadcastIntent}}
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:Off
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
D/PMS     (  903): acquireWL(44419fb0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  903): updateScreenOn: false
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/SmartSyncUtils( 4195): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4195): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4195): isEpsOn(), nState = 0
W/ContextImpl( 4195): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42763be0
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42763be0, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42763be0, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  903):    returned true
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42763be0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiService(  903): New client listening to asynchronous messages
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  903): releaseWL(44419fb0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42764128 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42764128 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1318): service - mHandler: cancel location update
,D/AutoSetting( 1318): service -           changes count: 0
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): acquireWL(434914d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(434914d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(43ec2e88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(43ec2e88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOff
,I/jxcore-log( 4412): Toggling radios to true
I/jxcore-log( 4412): 
,D/BluetoothAdapter( 4412): enable(): BT is already enabled..!
,D/WifiManager( 4412): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=4412, uid=10389
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1276
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 3(ms)
D/WifiManager( 4412): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
D/WifiManager( 4412): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): TDLS: Tear down peers
I/wpa_supplicant( 1157): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4412): Radios toggled
I/jxcore-log( 4412): 
I/jxcore-log( 4412): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4412): 
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1157): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1157): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7992bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1157): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1157): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplican,t port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  903):    returned true
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiPerfLock(  903): release()
D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/PMS     (  903): acquireWL(4391a370): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19976 mDataStallAlarmIntent=null
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): Fast associate: Old scan results
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  903):    returned true
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
D/UsbnetStateTracker(  903): isAvailable+-
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
,D/WifiNative-wlan0(  903): doBoolean: SET pno 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): CTRL_IFACE SET 'pno'='1'
,D/WISPrService( 4052): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiService(  903): New client listening to asynchronous messages
,D/WISPrService( 4052): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4052): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4052): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1157): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1157): nl80211: Event message available
,D/wpa_supplicant( 1157): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  903):    returned true
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,V/NativeCrypto( 1358): Read error: ssl=0x640451d0: I/O error during system call, Connection timed out
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
D/wpa_supplicant( 1157): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 3
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 1
I/wpa_supplicant( 1157): wpa_s->is_screen_on 0
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): selected network = 1
D/wpa_supplicant( 1157): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb79944e8  current_ssid=0x0
D/wpa_supplicant( 1157): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1157): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1157): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1157): check if in concurrent case
I/wpa_supplicant( 1157): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
V/NativeCrypto( 1358): SSL shutdown failed: ssl=0x640451d0: I/O error during system call, Broken pipe
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  903): doString: LIST_DONGLES
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1157): RSN: PMKSA cache search - network_ctx=0xb79944e8 try_opportunistic=0
D/wpa_supplicant( 1157): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1157): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1157): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1157): nl80211: Unsubscribe mgmt frames handle 0xb7993718 (mode change)
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1157): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7993718
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb7993718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1157):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157):   * freq=2412
D/wpa_supplicant( 1157):   * Auth Type 0
D/wpa_supplicant( 1157):   * WPA Versions 0x2
D/libc    (  363): [NET] entry_id:3   entry:0xb7969320  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7968fd8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7969428  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb7969240  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb79690e8  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb7964f60  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1157): nl80211: Connect request send successfully
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd, 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/PMS     (  903): acquireWL(438c3520): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (376) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-47
I/wpa_supplicant( 1157): tsf=0000000022011508
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-51
I/wpa_supplicant( 1157): tsf=0000000103094195
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2427
I/wpa_supplicant( 1157): level=-81
I/wpa_supplicant( 1157): tsf=0000000022011540
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ####
D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  903): == begin of scan result ==
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 22011508, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 103094195, distance: ?(cm), distanceSd: ?(cm)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 22011540, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 3 to mScanResults
D/PMS     (  903): acquireWL(4387b360): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
D/WifiNative-wlan0(  903): doBoolean: SET pno 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1157): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (3) end of scan result ==
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1157): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1157): Failed to initiate AP scan
I/wpa_supplicant( 1157): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  903):    returned true
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1358/10029)
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/BatSI   (  903): WIFI scan started for: 450a0300 uid:1000
D/WirelessDisplayService(  903): getDiscoveryDongleList
I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/PMS     (  903): releaseWL(438c3520): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,D/PMS     (  903): releaseWL(4387b360): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): nl80211: Event message available
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1157): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Connect event
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1157): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1157): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/WifiStateMachine(  903): Associated
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
D/wpa_supplicant( 1157): TDLS: Remove peers on association
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,D/Tethering(  903): interfaceStatusChanged wlan0, true
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=1
,D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1157): EAPOL: enable timer tick
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1157): getPrivFuncNum +	
,I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1157): Get randomness: len=32 entropy=2
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb79939f0 key_idx=0 set_tx=1 seq_len=6 key_len=16,
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f18b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1157):    broadcast key
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
,I/wpa_supplicant( 1157): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1157): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1157): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,E/wpa_supplicant( 1157): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1157): set send_ind_to_ndc = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1157): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1157): EAPOL authentication completed successfully
I/wpa_supplicant( 1157): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
,D/Tethering(  903): interfaceStatusChanged wlan0, true
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
,D/WISPrService( 4052): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4052): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiNative-wlan0(  903): doBoolean: SET pno 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  903):    returned true
,D/DhcpStateMachine(  903): [StoppedState] Start DHCP
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1,
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1157): Power_Mode_Type mode = 1
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true,
D/wpa_supplicant( 1157): nl80211: Event message available
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 1157): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0,
D/wpa_supplicant( 1157): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
,E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
,D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(432ba7c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41dad240 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41dad240 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1,
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4492 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  903): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/PMS     (  903): acquireWL(43934518): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(43934518): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTING
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.backuptransport (1597/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4251/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4251/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,I/MusicStore( 4492): Database version: 95
,W/ContextImpl( 4492): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4492): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/wpa_supplicant( 1157): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1157): EAPOL: disable timer tick
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4492): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4492): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4492): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4492, uid=10154, userID:0
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0,
,I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/MediaRouterService(  903): Client com.google.android.music (pid 4492): Registered
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
I/MediaRouter( 4492): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  903): releaseWL(432ba7c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4492/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2680/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4532 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  903): gateway: /192.168.1.1
,D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
,D/MediaRouter( 4492): getSelectedRoute
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  903): WAN detection
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4492/10154)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
,I/NetworkMonitor( 4492): type=WIFI subType= reason=null isConnected=false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/MDST    (  903): default: setTeardownRequested(true)
D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4052): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@424a7c00
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ACRA    ( 4532): ACRA is enabled for com.facebook.katana, intializing...
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/ACRA    ( 4532): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4532): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4492, uid=10154, userID:0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(443ff8e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  903): acquireWL(443ca9f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,D/Process (  903): killProcessQuiet, pid=4173
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
D/PMS     (  903): releaseWL(443ff8e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
I/ActivityManager(  903): Killing 4173:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,W/SystemClassLoaderAdder( 4532): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4532): Preparing secondary program dexes.
V/DexLibLoader( 4532): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4532): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4532): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4532): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4532): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,W/DexLibLoader( 4532): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4532): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4532): Dex already copied
D/OdexVerifier( 4532): Odex verification is skipped.
,V/DexLibLoader( 4532): Creating class loader,
V/DexLibLoader( 4532): Finished creating class loader
V/DexLibLoader( 4532): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4532): Dex already copied
D/OdexVerifier( 4532): Odex verification is skipped.,
,V/DexLibLoader( 4532): Creating class loader
,V/DexLibLoader( 4532): Finished creating class loader
V/DexLibLoader( 4532): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4532): Dex already copied
D/OdexVerifier( 4532): Odex verification is skipped.
,V/DexLibLoader( 4532): Creating class loader
,V/DexLibLoader( 4532): Finished creating class loader
V/DexLibLoader( 4532): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4532): Dex already copied
D/OdexVerifier( 4532): Odex verification is skipped.
,V/DexLibLoader( 4532): Creating class loader
V/DexLibLoader( 4532): Finished creating class loader
,V/DexLibLoader( 4532): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4532): DexLibLoader.ensureDexLoaded took 18 ms
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(443ca9f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ActivityManager(  903): Recipient 4173
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,W/dalvikvm( 4532): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4532): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4532): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4532): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4532): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4532): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4532): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4532): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/PMS     (  903): releaseWL(4391a370): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
V/Tethering(  903): bSetPropertyMultiRAB:false
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/CaptivePortalTracker(  903): NoActiveNetworkState
W/dalvikvm( 4532): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.backuptransport (1597/10029)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4492/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,I/NetworkMonitor( 4492): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/PMS     (  903): acquireWL(42daa6c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3829/10053)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4251/10100)
D/PMS     (  903): acquireWL(427b5258): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4251/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/PMS     (  903): releaseWL(427b5258): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): releaseWL(42daa6c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,E/FbInjectorInitializer( 4532): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4532): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4532): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4532): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4532): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=3762
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3762:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3762
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1318): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4566 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1318): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/AutoSetting( 1318): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1318): service - onStartCommand() check timezone in 30000
,W/fb4a(:<default>):UserScope( 4532): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4532): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4532): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4566): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4566): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4566): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4566): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4580 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3986
,I/ActivityManager(  903): Killing 3986:com.google.android.talk/u0a111 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
,D/PMS     (  903): acquireWL(43afc3c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43af8cc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43afc3c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1453126527304 min interval config: 0 actual interval: 52769
I/CheckinService( 2176): Checking schedule, now: 1453126580078 next: 1453126557269
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4595 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=4221
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4221:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1453126523557
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3986
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/ActivityManager(  903): Recipient 4221
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4532): Grow heap (frag case) to 9.953MB for 84664-byte allocation
E/dalvikvm( 4532): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4532): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  903): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4595): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4595): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4532): Grow heap (frag case) to 9.968MB for 28144-byte allocation
E/dalvikvm( 4532): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4532): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4532): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4532): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
W/GAV2    ( 4595): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/dalvikvm( 4532): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4532): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4532): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4532): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4532): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4532): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4532): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4532): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4532): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4532): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4532): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4532): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4595): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4595): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4532): Grow heap (frag case) to 10.014MB for 39954-byte allocation
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4532): Grow heap (frag case) to 10.090MB for 79892-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4595/10151)
,V/WebViewChromiumFactoryProvider( 4595): Binding Chromium to main looper Looper (main, tid 1) {41b23078}
,I/LibraryLoader( 4595): Expected native library version number "",actual native library version number ""
,I/chromium( 4595): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4595): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4595): BLUETOOTH permission is missing!
D/PMS     (  903): acquireWL(4262eef8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): acquireWL(4241dd88): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): releaseWL(4241dd88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4595): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4595): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4595): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4595): Local Branch: 
I/Adreno-EGL( 4595): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4595): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4595):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4412): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4412): 
I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4629 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4595): Starting up...
,I/dalvikvm-heap( 4532): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4595/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4595/10151)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43dbf028 u0 ReceiverList{43e0b068 4532 com.facebook.katana/10027/u0 remote:4337c2d8}}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43dbf028 u0 ReceiverList{43e0b068 4532 com.facebook.katana/10027/u0 remote:4337c2d8}}
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42351c18 u0 ReceiverList{42351bd8 4532 com.facebook.katana/10027/u0 remote:43284250}}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4029/10160)
,W/dalvikvm( 4629): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4629): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4629): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4629): install
,I/MultiDex( 4629): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/Process (  903): killProcessQuiet, pid=4251
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4029/10160)
,I/ActivityManager(  903): Killing 4251:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4629): loading existing secondary dex files
,I/MultiDex( 4629): load found 3 secondary dex files
,I/MultiDex( 4629): install done
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1157): Change stage from stage0 to stage1
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
I/ActivityManager(  903): Recipient 4251
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
W/dalvikvm( 4629): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4629): VFY: unable to resolve instance field 36
W/dalvikvm( 4629): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,V/JNIHelp ( 4629): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2680/10021)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(4385be68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(4385be68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1318): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4566): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/MobileConnectivityChangeReceiver( 4566): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1318): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1318): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1318): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4595/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4532): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4029/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4029/10160)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4532): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4029): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
I/ProviderInstaller( 4629): Installed default security provider GmsCore_OpenSSL
,W/ContextImpl( 4532): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,W/dalvikvm( 4629): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4629): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/MDM     ( 1223): [116] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2176): Restart initialization of location
D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,W/dalvikvm( 4629): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4629): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4629): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4629): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4629): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  903): acquireWL(43175970): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(43175970): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4629): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=1169026142
,I/WVCdm   (  370): CdmEngine::CloseSession
,W/Settings( 4629): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4629/10029)
,I/jxcore-log( 4412): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4412): 
,I/jxcore-log( 4412): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4412): 
,I/Adreno-EGL( 4629): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4629): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4629): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4629): Local Branch: 
I/Adreno-EGL( 4629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4629): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4629):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4412): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4412): 
,I/jxcore-log( 4412): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4412): 
,I/jxcore-log( 4412): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4412): 
,I/jxcore-log( 4412): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4412): 
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=1468847027
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/Adreno-EGL( 4629): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4629): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4629): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4629): Local Branch: 
I/Adreno-EGL( 4629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4629): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4629):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4629): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4629): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4629): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4629): Local Branch: 
I/Adreno-EGL( 4629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4629): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4629):                  aa63bbd948f41d15fc72f585e
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6be8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/104.81.130.175
,I/jxcore-log( 4412): Test app app.js loaded
I/jxcore-log( 4412): 
,D/PMS     (  903): releaseWL(424e5ca8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4412): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =111a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 280
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2176): Sending checkin request (12210 bytes)
,W/dalvikvm( 4412): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4412): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4412): BLE advertisement is supported
I/jxcore-log( 4412): 
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  903): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=4 [22][1][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2176): Checking schedule, now: 1453126582482 next: 1453649519477
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1453126582505
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,D/PMS     (  903): releaseWL(43af8cc8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  903): acquireWL(4378b9d8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1358): [NET] getaddrinfo-,err=8
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1358): [NET] getaddrinfo-, 1
D/libc    ( 1358): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =830d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 234
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1358): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1358): [NET] getaddrinfo-,err=8
,D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1358): [NET] getaddrinfo-,err=8
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,W/fb4a(:<default>):UserScope( 4532): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4532): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=33 [6][2][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1157): Change stage from stage1 to stage0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/PMS     (  903): acquireWL(436850e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  903): releaseWL(4378b9d8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
,D/PMS     (  903): releaseWL(436850e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43a82668): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
,D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,D/PMS     (  903): releaseWL(43a82668): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4532): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4532/10027)
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  903): releaseWL(4262eef8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=25 [4][1][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(443cddc0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4492 10154 null
,W/ContextImpl( 4492): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4492, uid=10154, userID:0
,I/MusicLeanback( 4492): Conditions not met for autocaching.
,I/MusicLeanback( 4492): Stop autocaching.
D/PMS     (  903): releaseWL(443cddc0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4492): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4275
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4275:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4275
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4595): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  903): Killing 4238:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4238
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4238
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3829
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3829:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3829
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4691 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsUpdated
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,E/ExternalAccountType( 1339): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4691): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4691): MmsConfig.loadMmsSettings
,W/dalvikvm( 4691): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4691): VFY: unable to resolve instance field 36
,W/dalvikvm( 4691): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4691): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  903): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4714 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4691, uid=10111, userID:0
,W/Settings( 4691): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4691, uid=10111, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4691, uid=10111, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4691, uid=10111, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4691, uid=10111, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4691, uid=10111, userID:0
,D/PMS     (  903): acquireWL(42ce0968): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4691 10111 null
,D/MessageFrequencyProvider( 4714): onCreate
,V/GetPrviateResource( 4714): GetPrviateResource
,V/GetPrviateResource( 4714): GetPrviateResource
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
,D/MmsCustomizationProvider( 4714): query uri: content://htc-mms-customization/mms-ua/ua_string
I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/IcingCorporaProvider( 2783): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MmsCustomizationProvider( 4714): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  903): acquireWL(4347aa10): PARTIAL_WAKE_LOCK  AsyncService 0x1 4029 10160 null
,I/Babel   ( 4691): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4691): MmsConfig.loadFromDatabase
D/PMS     (  903): acquireWL(43b41440): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4029): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  903): releaseWL(43b41440): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(4347aa10): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  903): acquireWL(424e7db0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4029): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
D/PMS     (  903): releaseWL(42ce0968): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
E/Babel   ( 4691): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4691): MmsConfig.loadFromResources
,E/Babel   ( 4691): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4691): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  903): Resuming delayed broadcast
,D/MessageCustFlag( 4714): sense_version=6.0
,D/Process (  903): killProcessQuiet, pid=4293
D/BTAccessoryUtil( 4714): createReceiver
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BTAccessoryUtil( 4714): registerReceiver return intent = null
D/MessageCustFlag( 4714): sku_id=99
,W/SystemReader( 4714): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  903): Killing 4293:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ProviderInstaller( 4691): Installed default security provider GmsCore_OpenSSL
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Messaging( 4714): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4714): networkCode: 
,D/MessageCustFlag( 4714): sku_id=99
D/MmsConfig( 4714): SIE smsPri: null
,D/MmsConfig( 4714): networkCode: 
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  903): Recipient 4293
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcTelephonyCapability( 4714): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4714): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4714): getRATByHtcTelephonyCapability:1
W/SystemReader( 4714): Cannot find qct_8960_interface, use default value instead
I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  903): Resuming delayed broadcast
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  903): Unable to load service info ResolveInfo{43afd860 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2783): UpdateCorporaTask done [took 749 ms] updated apps [took 749 ms] 
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bb3db0 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  903): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  903): applying state to connected service
D/PMS     (  903): acquireWL(443a3538): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  903): applying state to connected service
D/PMS     (  903): releaseWL(443a3538): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43940ca8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43a010e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43940ca8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43a010e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bb3db0 -
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
D/PMS     (  903): releaseWL(424e7db0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4714): mNeedToUpdateDate2 start
,D/MmsConfig( 4714): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4714): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4714): 
D/MmsAsyncWorkHandler( 4714): HM tk = 20001
,D/ReportIndicatorCache( 4714): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4714): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b2f160
,I/Messaging( 4714): mccmnc> 
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4714): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4714): [DraftCache/1] refresh
,D/MmsConfig( 4714): networkCode: 
,D/Messaging( 4714): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4714): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4714): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4714): createReceiver
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4714): sense_version=6.0
,D/Messaging( 4714): mNeedToUpdateDate2: false
,D/Jerry   ( 4714): start to preload cursor >>>>>>>
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1240): sku_id=99
,D/TelephUtils( 1240): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/MmsProvider( 1240): Update uri=content://mms, match=0
,V/MmsProvider( 1240): selection=st=129 AND m_type!=134
,D/Messaging( 4714): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4714): TransactionService is going to be woken up.
,D/DraftCache( 4714): [DraftCache/469] rebuildCache
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,V/TransactionService( 4714): 1-Creating TransactionService
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/Messaging( 4714): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
V/TransactionService( 4714): onStartCommand: 1
,D/MmsSystemEventReceiver( 4714): unRegisterForConnectionStateChanges
V/TransactionService( 4714): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4714): Loading previous transactions.
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): device_type: 1
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1240): URI_DRAFT
D/TransactionService( 4714): Force set service start id to 1
V/TransactionService( 4714): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4714): unRegisterForConnectionStateChanges
D/TransactionService( 4714): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4714): Destroying TransactionService
,V/TransactionService( 4714): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/DraftCache( 4714): hasDraft() = false mNeedNotifyChange = true
D/Messaging( 4714): ViewCache CreatePreload
D/Messaging( 4714): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4714): [DraftCache/469] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4714): 
D/MmsAsyncWorkHandler( 4714): HM tk = 20002
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1240): sku_id=99
,D/Cust_MMSMS( 4714): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4714): def_index: 0
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1240): sku_id=99
,D/MsgPreferenceUtils( 4714): globalIndex = 1
D/MsgPreferenceUtils( 4714): phone state: true
D/MsgPreferenceUtils( 4714): sd state: false
,D/MsgPreferenceUtils( 4714): vIndex = 0
,D/PMS     (  903): acquireWL(42465c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  903): sending alarm PendingIntent{443d83c0: PendingIntentRecord{41c52e80 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121732, Int=0
,D/PMS     (  903): releaseWL(42465c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43933258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=7 [14][1][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(439b5670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4691): Thread[GAThread,5,main]: No campaign data found.
D/PMS     (  903): releaseWL(439b5670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(43933258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(435efc20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
D/PMS     (  903): releaseWL(435efc20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(43a91be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(43a0c200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43b15ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1453126595971 tag=VacuumService
D/PMS     (  903): releaseWL(43a91be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43a0c200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(443ffd20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(43b15ec8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(443ffd20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(43acd848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
D/PMS     (  903): releaseWL(43acd848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(439cbcc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,D/PMS     (  903): releaseWL(439cbcc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43bc1220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(43bc1220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(43e04b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(43b0e518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43b0e518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(4263d2d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(43e04b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43afef60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,D/PMS     (  903): releaseWL(43afef60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 14388 seconds from now (1453126596547)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL,
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8003 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): releaseWL(4263d2d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43a08178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,D/PMS     (  903): releaseWL(43a08178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(43a0dbc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,D/PMS     (  903): releaseWL(43a0dbc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(439f9c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1114): closing low battery warning: level=100
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(439f9c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43ab6b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  903): sending alarm PendingIntent{42a62200: PendingIntentRecord{426ec9a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=133008, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  903): releaseWL(43ab6b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1318): service - mHandler: update timezone
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1585): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1497): service - mHandler: update timezone
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41c73ed8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 2 8 3 11
,D/AutoSetting( 1318): service - has update message, not stop
,D/AutoSetting( 1318): service - mHandler: update timezone
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1497): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1497): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1497): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1497): service - mHandler: update timezone
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/DotMatrix( 1585): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1497): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1497): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1497): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f5cf98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 3 7 3 11
,D/PMS     (  903): acquireWL(43942cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4255cf20: PendingIntentRecord{424515a0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141581, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{44517ed8: PendingIntentRecord{4255e8a0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453126609106, Int=1800000
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(43a59e30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1fdf +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  903): acquireWL(43d108b8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(43942cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
D/PMS     (  903): acquireWL(43521b58): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(43d108b8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2176): Aggregate from 1453126580137 (log), 1453124809023 (data)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 17
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023618
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024184
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024187
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024191
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024202
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025664
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025677
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028455
,D/PMS     (  903): releaseWL(43521b58): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): acquireWL(426d2430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b4d328: PendingIntentRecord{41b3b888 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=145977, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(426d2430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(43a59e30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43b363b0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  903): acquireWL(444222b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(444222b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1318): service - handleMessage() stop self
,D/AutoSetting( 1318): service - handleMessage() quit looper
,D/AutoSetting( 1318): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=4328
,I/ActivityManager(  903): Killing 4328:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 4328
,D/AutoSetting( 1497): service - handleMessage() stop self
,D/AutoSetting( 1497): service - onDestroy() END
,D/AutoSetting( 1497): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4343
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4343:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4343
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43d30348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10027}
,V/AlarmManager(  903): sending alarm PendingIntent{43299fc0: PendingIntentRecord{438850b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=169911, Int=0
,D/PMS     (  903): releaseWL(43d30348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(43b26150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43b26150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1358): disconnect managed GoogleApiClient
,D/PMS     (  903): acquireWL(43afc410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b4d328: PendingIntentRecord{41b3b888 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=205978, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43afc410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43af8c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43af8c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43ad0470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43ad0470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(43ab4378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41b4d328: PendingIntentRecord{41b3b888 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=265978, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43ab4378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43a6deb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43a6deb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4412): --= Surplus to requirements =--
I/jxcore-log( 4412): 
I/jxcore-log( 4412): ****TEST TOOK:  ms ****
I/jxcore-log( 4412): 
,I/jxcore-log( 4412): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4412): 
,D/CustomizationManager( 4809): ====startRecUseTime====
D/htc.customization.log.level( 4809):  is 
,W/CustomizationLogLevel( 4809): Level value is invalid, use default level 2
,D/CustomizationManager( 4809):  Read ACC file spent 0.107 (s)
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4809): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4809): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4809): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4809): Parsing tag category name = system,
I/CustomizationCIDLoader( 4809): Parsing tag category name = application,
I/CustomizationCIDLoader( 4809): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4809): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4809): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4809): Parsing tag category name = ACC,
I/CustomizationCIDLoader( 4809): Parsing tag category name = Settings
D/CustomizationManager( 4809):  Read CID file spent 0.163 (s)
,D/CustomizationManager( 4809):  All configurations done spent 0.163 (s)
,W/HtcNativeFlag( 4809): Fail to get flag string for type 'customer', use default value,
W/HtcNativeFlag( 4809): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4809): Fail to get flag string for type 'language', use default value,
,W/HtcNativeFlag( 4809): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4809, uid=2000 user=0
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  903): killProcessQuiet, pid=4412
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  903): Killing 4412:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  903):   Force finishing activity ActivityRecord{4347c228 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  903): Copying FileAsset 0x6e19b870 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  903): channel '41c4a470 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  903): channel '41c4a470 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '41c4a470 com.test.thalitest.MainActivity (s)'
I/WindowManager(  903): WINDOW DIED Window{41c4a470 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 4412 uid 10389
,W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
,W/PackageSettings(  903): Skipping PackageSetting{42179be0 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  903): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  903): acquireWL(43891178): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
,D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PMS     (  903): releaseWL(43891178): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
,E/cutils-trace( 4809): Error opening trace file: No such file or directory (2)
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,E/ExternalAccountType( 1339): Unsupported attribute readOnly
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
,I/IcingCorporaProvider( 2783): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,W/Parcel  ( 1255): Reading a NULL string not supported here.
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4825 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  903): acquireWL(43a6deb8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2783): UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
,E/SQLiteDatabase( 4825): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4825): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4825): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4825): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4825): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4825): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4825): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4825): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4825): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4825): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4825): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4825): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4825): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4825): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4825): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4825): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4825): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4825): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4825): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4825): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4825): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4825): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4825): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4825): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4825): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4825): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4825): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4825): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4825): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4825): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4825): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4825): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4825): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4825): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4825): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4825): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4825): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4825): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4825): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4825): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4825): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4825): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4825): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4825): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4825): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4825): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4825): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4825): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4825): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4825): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4825): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4825): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4825): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4825): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4825): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4825): threadid=11: thread exiting with uncaught exception (group=0x416f0e30)
,E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4825): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4825): Process: com.google.android.apps.docs, PID: 4825
E/AndroidRuntime( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4825): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4825): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4825): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4825): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4825): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4825): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
,I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4843 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4825): killProcess, pid=4825
D/Process ( 4825): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  903): Recipient 4825
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4825) has died.
,W/ContextImpl( 4843): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4856 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4843): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4843): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4843): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4843): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4843): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4843): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4843): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4843): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4843): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4843): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4843): threadid=10: thread exiting with uncaught exception (group=0x416f0e30)
,E/ActivityManager(  903): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4843): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4843): Process: com.android.keychain, PID: 4843
E/AndroidRuntime( 4843): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4843): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4843): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4843): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4843): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4843): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4843): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4843): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4843): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4843): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4843): killProcess, pid=4843
,D/Process ( 4843): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453126798112.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
,D/AppTag  ( 4856): getInstance(Context context)
,D/AppTag  ( 4856): getInstance(Context context),
,D/AppTag  ( 4856): onCreate()
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  903): acquireWL(426a26a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4029 10160 null
,D/PMS     (  903): releaseWL(426a26a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Recipient 4843
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Process com.android.keychain (pid 4843) has died.
,W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,W/dalvikvm( 4067): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  903): killProcessQuiet, pid=3961
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3961:com.google.android.gm/u0a107 (adj 15): empty #17
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
I/ActivityManager(  903): Recipient 3961
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/ActivityManager(  903): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6639a540
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cae6300
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bb3db0 +
I/Prism.WidgetManager( 1271): onLoadItems() +
,W/dalvikvm( 2176): threadid=47: thread exiting with uncaught exception (group=0x416f0e30)
,E/DriveAsyncService( 2176): disk I/O error (code 3850)
E/DriveAsyncService( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2176): 	at java.lang.Thread.run(Thread.java:864)
,E/AndroidRuntime( 2176): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2176): Process: com.google.android.gms, PID: 2176
E/AndroidRuntime( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2176): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2176): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2176): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2176): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  903): App crashed! Process: com.google.android.gms
,D/Process ( 2176): killProcess, pid=2176
D/Process ( 2176): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/SQLiteDatabase( 2176): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2176): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2176): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2176): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2176): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2176): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2176): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
,I/ActivityManager(  903): Recipient 2176
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.gms (pid 2176) has died.
D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): handleWLDeath(43a6deb8): PARTIAL_WAKE_LOCK  Icing 0x1
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20998ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20996ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
,I/ActivityManager(  903): Resuming delayed broadcast
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20993ms
,W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30993ms
,E/SQLiteLog( 1358): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1358): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f71ad8
,W/dalvikvm( 1358): threadid=1: thread exiting with uncaught exception (group=0x416f0e30),
,E/AndroidRuntime( 1358): FATAL EXCEPTION: main
E/AndroidRuntime( 1358): Process: com.google.process.gapps, PID: 1358
E/AndroidRuntime( 1358): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1358): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1358): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1358): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1358): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1358): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1358): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1358): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1358): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1358): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1358): 	... 10 more
,E/ActivityManager(  903): App crashed! Process: com.google.process.gapps
,E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
,I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4887 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1358): killProcess, pid=1358
D/Process ( 1358): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 

```
