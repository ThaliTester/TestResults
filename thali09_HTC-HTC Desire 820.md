#### Test 55467363832a26e_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
,--------- beginning of /dev/log/system
D/PMS     (  908): acquireWL(445bbde0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(445bbde0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 4467): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4467): ====startRecUseTime====
D/htc.customization.log.level( 4467):  is 
W/CustomizationLogLevel( 4467): Level value is invalid, use default level 2
D/CustomizationManager( 4467):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4467): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4467): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4467): Parsing tag category name = system
I/CustomizationCIDLoader( 4467): Parsing tag category name = application
I/CustomizationCIDLoader( 4467): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4467): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4467): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4467): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4467): Parsing tag category name = Settings
D/CustomizationManager( 4467):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4467):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4467): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4467): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4467): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4467): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4467
D/PMS     (  908): acquireHCC(44a5bbb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(42e5d7d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x62b2c228 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1145773264
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424ed948
D/PMS     (  908): acquireWL(438c9ba8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4479 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1267): [trimMemory] 20
W/asset   ( 4479): Copying FileAsset 0x5c871428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4479): Binding Chromium to main looper Looper (main, tid 1) {424046a0}
I/LibraryLoader( 4479): Expected native library version number "",actual native library version number ""
I/chromium( 4479): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4479): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(44bb8910): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
D/PMS     (  908): acquireWL(44baa388): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
,D/PMS     (  908): releaseWL(44bb8910): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44aa5b88:true
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4479): 1111600760: getState(). Returning 12
,I/Adreno-EGL( 4479): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4479): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4479): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4479): Local Branch: 
I/Adreno-EGL( 4479): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4479): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4479):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4479): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4479): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4479): CordovaWebView is running on device made by: HTC
,W/AwContents( 4479): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  908): Disable input method client, pid=1267
,I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +423ms
W/ResourceType( 4479): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4479): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4244c528, mServedView=org.apache.cordova.engine.SystemWebView{42412190 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  908): Enable input method client, pid=4479
W/AwContents( 4479): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  908): releaseWL(438c9ba8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4479): Set native->JS mode to OnlineEventsBridgeMode
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/jxcore_app_log( 4479): JniHelper::setJavaVM(0x41fc4010), pthread_self() = 1663115728
,D/JX-Cordova( 4479): jxcore cordova android initializing
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.589MB for 96598-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.663MB for 144892-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.784MB for 217334-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 11.958MB for 325996-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 12.229MB for 488990-byte allocation
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 13.243MB for 1100216-byte allocation
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 14.107MB for 1650320-byte allocation
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 15.477MB for 2475476-byte allocation
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  908): releaseHCC(44a5bbb0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
,D/PMS     (  908): releaseHCC(42e5d7d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/PMS     (  908): acquireWL(44b1baf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=99 rxSum=87} preTxRxSum={txSum=99 rxSum=87}
D/WifiDataStallTracker(  908): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=20143 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20144 delay=15s
V/AlarmManager(  908): sending alarm PendingIntent{42f97e00: PendingIntentRecord{42f0fbd8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105048, Int=0
D/PMS     (  908): releaseWL(44b1baf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/dalvikvm-heap( 4479): Grow heap (frag case) to 17.593MB for 3713210-byte allocation
,W/jxcore-log( 4479): Initializing JXcore engine
,W/jxcore-log( 4479): JXcore engine is ready
,W/jxcore-log( 4479): Starting JXcore engine
,W/jxcore-log( 4479): Platform android
W/jxcore-log( 4479): 
,W/jxcore-log( 4479): Process ARCH arm
W/jxcore-log( 4479): 
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a553d0
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a553d0, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42750b48
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@42fdcaa0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,W/PMS     (  908): mWirelessDisplayManager is null
D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/PMS     (  908): releaseWL(44baa388): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 337ms
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42e4ad70)
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=4479
D/PMS     (  908): acquireWL(449f3428): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  908): releaseWL(449f3428): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  908): wakingUp
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
I/WindowManager(  908): No lock screen! windowToken=null
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  908): acquireWL(42d820d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMN     (  908): onScreenOn
D/PMS     (  908): releaseWL(42d820d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/MtpService( 2718): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1254): applyRouting - 0
,D/MtpService( 2718): [MTP][onReceive]-
D/NfcService( 1254): applyRouting -2
,D/AutoSetting( 1316): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  908): acquireWL(42533140): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  908): releaseWL(42533140): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/TetherSettings( 3849): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3849): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3849): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3849): Cust_ConnectToPC   : spcsc>false
D/        ( 3849): Cust_ConnectToPC   : IPT>true
D/        ( 3849): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3849): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3849): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3849): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3849): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20145 delay=15s
,I/PSReceiver( 3849): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3849): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3849): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3849):  defaultType:0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): SET_SCREEN_ON:On
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
W/ContextImpl( 3849): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1184): BG scan when screen On
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1184): wpa_supplicant_scan enter
I/wpa_supplicant( 1184): Match BG scan, scan!
I/wpa_supplicant( 1184): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1184): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1184): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1116): stop update clock
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/SRS_Proc(  363): ParamSet string: screen_state=on
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  908): updateScreenOn: false
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4535 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/jxcore-log( 4479): JXcore Cordova bridge is ready!
I/jxcore-log( 4479): 
,W/jxcore-log( 4479): JXcore engine is started
,I/chromium( 4479): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourceType( 4479): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4479): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{42412190 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): acquireWL(43d557d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43d557d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): acquireWL(42f30bc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1741): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): onScreenOn: 1452271997545
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1741): onScreenOn: 1452271997545
D/PMS     (  908): releaseWL(42f30bc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42ce1148): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4535 1000 null
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42750b48
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42750b48, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@42fdcaa0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4535): isEpsOn(), nState = 0
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(42c32220): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
D/PMS     (  908): releaseWL(42ce1148): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20145 mDataStallAlarmIntent=PendingIntent{42e60378: PendingIntentRecord{42f0fbd8 android broadcastIntent}}
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
D/PMS     (  908): acquireWL(44ae07f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
,D/SmartSyncUtils( 4535): getMobilePolicyEnabled, result = true
,I/ActivityManager(  908): Killing 3886:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=3886
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 3886
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  908): Activity pause timeout for ActivityRecord{449d9b80 u0 com.test.thalitest/.MainActivity t2}
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): SET_SCREEN_ON:Off
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1184): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 95
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:133, mTXpacketCount:133, avgLinkspeed:19,mAvgTxRate54
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
V/SRS_Proc(  363): ParamSet string: screen_state=off
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1236): start background delete task...
D/ContactMessageStore( 1236): size: 0 , 0
,D/ContactMessageStore( 1236): Background delete complete
,W/ContextImpl( 4535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4535): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4535): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4535): isEpsOn(), nState = 0
D/WifiService(  908): New client listening to asynchronous messages
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42fdcaa0
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42fdcaa0, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42fdcaa0, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42fdcaa0
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42fdcf70 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42fdcf70 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1316): service - mHandler: cancel location update
,D/AutoSetting( 1316): service -           changes count: 0
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] getTotalRam: 1873 Mb
D/PMS     (  908): acquireWL(43cb2da8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43cb2da8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(449d61e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(449d61e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1741): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1741): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1741): onScreenOff
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0],
,I/jxcore-log( 4479): Toggling radios to true
I/jxcore-log( 4479): 
,D/BluetoothAdapter( 4479): enable(): BT is already enabled..!
,D/PMS     (  908): releaseWL(44ae07f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiManager( 4479): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1488
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
,W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): ,	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 2(ms)
D/WifiManager( 4479): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4479): reconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): TDLS: Tear down peers
,I/wpa_supplicant( 1184): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4479): Radios toggled
I/jxcore-log( 4479): 
D/WifiService(  908): setWifiEnabled: true pid=4479, uid=10389
,E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  908): New client listening to asynchronous messages
D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4479): Received device characteristics:
I/jxcore-log( 4479): Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4479): Bluetooth name: HTC Desire 820
I/jxcore-log( 4479): Device name: HTC-HTC Desire 820
I/jxcore-log( 4479): 
I/jxcore-log( 4479): Perf Test app loaded loaded
I/jxcore-log( 4479): 
I/jxcore-log( 4479): check test folder
I/jxcore-log( 4479): 
I/jxcore-log( 4479): found test : ./testFindPeers.js
I/jxcore-log( 4479): 
,I/jxcore-log( 4479): found test : ./testSendData.js
I/jxcore-log( 4479): 
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1184): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1184): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1184): TDLS: Remove peers on disassociation
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7577bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1184): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1184): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1184): nl80211: Ignore disconnect event triggered during reassociation
D/wpa_supplicant( 1184): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1184): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1184): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1184): nl80211: Survey data missing
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1184): Sorted scan results
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1184): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1184): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
D/wpa_supplicant( 1184): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1184): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1184): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1184): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1184): Add randomness: count=8 entropy=3
I/wpa_supplicant( 1184): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1184): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1184): nl80211: Survey data missing
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
D/WifiNative-wlan0(  908):    returned true
D/wpa_supplicant( 1184): Sorted scan results
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1184): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1184): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
D/wpa_supplicant( 1184): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1184): Add randomness: count=9 entropy=4
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1184): Add randomness: count=10 entropy=5
D/wpa_supplicant( 1184): Add randomness: count=11 entropy=6
D/wpa_supplicant( 1184): Add randomness: count=12 entropy=7
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1184): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1184): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1184): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1184): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1184): wpa_supplicant_pick_network+
I/wpa_supplicant( 1184): clear disabled list - type=1
I/wpa_supplicant( 1184): No suitable network found
W/wpa_supplicant( 1184): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1184): State: DISCONNECTED -> INACTIVE
D/WifiPerfLock(  908): release()
D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  908): acquireWL(43038940): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =INACTIVE
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiP2pService(  908): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@438e29a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@438e29a0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@438e29a0 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  908): [RunningState] Stop DHCP
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  908): doBoolean: RECONNECT
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): wpa_supplicant_pick_network+
I/wpa_supplicant( 1184): Selecting BSS from priority group 1
I/wpa_supplicant( 1184): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1184): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1184): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1184): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1184):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1184):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1184): Start print parameters
I/wpa_supplicant( 1184): wpa_s->wpa_state is 0
I/wpa_supplicant( 1184): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1184): isConcurrentMode() is 0
I/wpa_supplicant( 1184): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1184): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1184): wpa_s->bt_a2dp_status is 0
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1184): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1184): wpa_s->reassociate is 1
I/wpa_supplicant( 1184): wpa_s->is_screen_on 0
I/wpa_supplicant( 1184): wpa_s->ifname wlan0
I/wpa_supplicant( 1184): End print parameters
I/wpa_supplicant( 1184): selected network = 1
D/wpa_supplicant( 1184): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0xb75794e8  current_ssid=0x0
D/wpa_supplicant( 1184): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1184): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1184): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1184): check if in concurrent case
I/wpa_supplicant( 1184): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1184): RSN: PMKSA cache search - network_ctx=0xb75794e8 try_opportunistic=0
D/wpa_supplicant( 1184): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1184): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1184): State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 1184): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1184): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20146 mDataStallAlarmIntent=null
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1184): nl80211: Unsubscribe mgmt frames handle 0xb7578718 (mode change)
D/wpa_supplicant( 1184): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7578718
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7578718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1184):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1184):   * freq=2412
D/wpa_supplicant( 1184):   * Auth Type 0
D/wpa_supplicant( 1184):   * WPA Versions 0x2
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1184): nl80211: Connect request send successfully
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): Enter handleNetworkDisconnect
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
D/UsbnetStateTracker(  908): isAvailable+-
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/MDST    (  908): default: reconnect()
D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  908): New client listening to asynchronous messages
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  908): Exit handleNetworkDisconnect
D/WifiNative-wlan0(  908): doBoolean: SET pno 1
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1184): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1184): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  908):    returned false
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
V/NativeCrypto( 1364): Read error: ssl=0x663fed88: I/O error during system call, Connection timed out
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1184): reply (518) for get BSS: id=0
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1184): freq=5220
I/wpa_supplicant( 1184): level=-48
I/wpa_supplicant( 1184): tsf=0000000108020575
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG7005g
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=1
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): freq=2412
I/wpa_supplicant( 1184): level=-56
I/wpa_supplicant( 1184): tsf=0000000108020595
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG700
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=2
I/wpa_supplicant( 1184): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1184): freq=2412
I/wpa_supplicant( 1184): level=-81
I/wpa_supplicant( 1184): tsf=0000000108020604
I/wpa_supplicant( 1184): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1184): ssid=Gonzos
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=3
I/wpa_supplicant( 1184): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1184): freq=2437
I/wpa_supplicant( 1184): level=-87
I/wpa_supplicant( 1184): tsf=0000000108020614
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1184): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1184): ####
V/NativeCrypto( 1364): SSL shutdown failed: ssl=0x663fed88: I/O error during system call, Broken pipe
D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  356): [NET] entry_id:3   entry:0xb8894108  removed 
D/WifiStateMachine(  908): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -200, -1
D/libc    (  356): [NET] entry_id:4   entry:0xb88942f0  removed 
D/libc    (  356): [NET] entry_id:1   entry:0xb8894428  removed 
D/libc    (  356): [NET] entry_id:5   entry:0xb8893fd8  removed 
D/libc    (  356): [NET] entry_id:2   entry:0xb88944f0  removed 
D/libc    (  356): [NET] entry_id:6   entry:0xb888ff88  removed 
D/libc    (  356): *************************
D/libc    (  356): *** DNS CACHE FLUSHED ***
D/libc    (  356): *************************
D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WirelessDisplayService(  908): getDiscoveryDongleList
D/PMS     (  908): acquireWL(43d2d648): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108020575, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 108020595, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
D/WifiStateMachine(  908): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 108020604, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -87, frequency: 2437, timestamp: 108020614, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 4 to mScanResults
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
V/ScoreHelper(  908): Only print Top 10 in ApScanList
V/ScoreHelper(  908):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  908):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  908):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  908):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  908):  + computeScore(NG700): 1
,D/WifiStateMachine(  908): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:2
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/WifiManager( 1221): getScanResults enter 
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/WifiStateMachine(  908): == begin of scan result ==
,D/WifiStateMachine(  908): == (4) end of scan result ==
D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  908): == begin of scan result ==
,D/WifiStateMachine(  908): == (4) end of scan result ==
D/PMS     (  908): acquireWL(445a9ac8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1364/10029)
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
D/WifiNative-wlan0(  908): doBoolean: SET pno 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='0'
I//system/bin/ip(  356): RTNETLINK answers: No such process
D/WifiNative-wlan0(  908):    returned true
I/logwrapper(  356): /system/bin/ip terminated by exit(2)
D/WifiNative-wlan0(  908): doBoolean: SCAN
,D/WirelessDisplayService(  908): getDiscoveryDongleList
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): wpa_supplicant_scan enter
I/wpa_supplicant( 1184): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1184): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  908):    returned true
E/wpa_supplicant( 1184): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1184): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1184): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1184): Failed to initiate AP scan
,I/wpa_supplicant( 1184): Failed to initiate AP scan, Failed_to_scan_counter:1
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/BatSI   (  908): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  908): releaseWL(43d2d648): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  908): releaseWL(445a9ac8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
,I/chromium( 4479): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  908): releaseWL(42c32220): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1184): nl80211: Connect event
D/wpa_supplicant( 1184): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1184): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1184): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1184): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1184): Add randomness: count=13 entropy=8
I/wpa_supplicant( 1184): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): TDLS: Remove peers on association
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1184): EAPOL: enable timer tick
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1184): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1184): Get randomness: len=32 entropy=9
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiStateMachine(  908): Associated
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb75789f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0db4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1184):    broadcast key
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1184): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1184): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1184): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1184): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1184): set send_ind_to_ndc = 0
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1184): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1184): EAPOL authentication completed successfully
I/wpa_supplicant( 1184): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
,D/Tethering(  908): interfaceLinkStateChanged wlan0, false
,D/Tethering(  908): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
,D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiStateMachine(  908): BSSID was changed, update WiFi database
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
,D/Tethering(  908): interfaceStatusChanged wlan0, true
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
,D/Tethering(  908): interfaceStatusChanged wlan0, true
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...,
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
,D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiNative-wlan0(  908): doBoolean: SET pno 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  908):    returned true
,D/DhcpStateMachine(  908): [StoppedState] Start DHCP
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(440b0ab0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 1
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1184): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:3,
,D/WifiNative-wlan0(  908):    returned null
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42f10908 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42f10908 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4576 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  908): NoActiveNetworkState
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTING
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
D/PMS     (  908): acquireWL(444ed988): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(444ed988): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10076)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  908): ipv4Default null
,I/Tethering(  908): No IPv4 upstream interface, giving up.
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
,D/wpa_supplicant( 1184): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1184): EAPOL: disable timer tick
,I/MusicStore( 4576): Database version: 95
,W/ContextImpl( 4576): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4576): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4576): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4576): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4576): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4576, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 4576): Registered
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
I/MediaRouter( 4576): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (4576/10154)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2718/10021)
,I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4596 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4576): getSelectedRoute
,I/NetworkMonitor( 4576): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4576/10154)
,D/ACRA    ( 4596): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  908): killProcessQuiet, pid=4140
,D/ACRA    ( 4596): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4596): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4576, uid=10154, userID:0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(4354ed68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(4354ed68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  908): Killing 4140:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/SystemClassLoaderAdder( 4596): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4596): Preparing secondary program dexes.
V/DexLibLoader( 4596): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4596): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4596): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4596): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4596): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4596): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4596): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4596): Dex already copied
D/OdexVerifier( 4596): Odex verification is skipped.
,V/DexLibLoader( 4596): Creating class loader
,V/DexLibLoader( 4596): Finished creating class loader
V/DexLibLoader( 4596): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4596): Dex already copied
D/OdexVerifier( 4596): Odex verification is skipped.
V/DexLibLoader( 4596): Creating class loader
V/DexLibLoader( 4596): Finished creating class loader
V/DexLibLoader( 4596): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4596): Dex already copied
D/OdexVerifier( 4596): Odex verification is skipped.
,V/DexLibLoader( 4596): Creating class loader
,V/DexLibLoader( 4596): Finished creating class loader
V/DexLibLoader( 4596): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4596): Dex already copied
D/OdexVerifier( 4596): Odex verification is skipped.
,V/DexLibLoader( 4596): Creating class loader
V/DexLibLoader( 4596): Finished creating class loader
,V/DexLibLoader( 4596): Verifying classes from secondary dexes.
,D/DexLibLoader( 4596): DexLibLoader.ensureDexLoaded took 19 ms
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4140
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(440b0ab0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  908): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  908): gateway: /192.168.1.1
D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1184): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -56, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  908): WAN detection
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3849): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  908): default: setTeardownRequested(true)
,D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1184): Change stage from stage0 to stage3
D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): syncGetConfiguredNetworks
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d88590
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
,D/libc    (  356): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  908): acquireWL(439c9500): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  356): RTNETLINK answers: No such file or directory
,I/logwrapper(  356): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  356): RTNETLINK answers: No such process
,I/logwrapper(  356): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(439c9500): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/dalvikvm( 4596): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4596): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4596): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4596): Verify
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4596): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4596): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4596): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=4265
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 4265:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4265
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
D/AutoSetting( 1316): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4647 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1316): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1316): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1316): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
,D/PMS     (  908): releaseWL(43038940): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
,D/MobileConnectivityChangeReceiver( 4647): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4647): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4647): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4647): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4661 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=4164
,I/ActivityManager(  908): Killing 4164:com.google.android.talk/u0a111 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,W/fb4a(:<default>):UserScope( 4596): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4596): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4647/10079)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4647/10079)
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/fb4a(:<default>):UserScope( 4596): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4647/10079)
,D/PMS     (  908): acquireWL(42f9d168): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1997 10029 WorkSource{10029 com.google.android.gms}
,I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): Found interface wlan0
D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4576): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  908): NoActiveNetworkState
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4576/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10076)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4647/10079)
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/PMS     (  908): acquireWL(44108508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(44224268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  908): Recipient 4164
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3959/10053)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4331/10100)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/PMS     (  908): releaseWL(44224268): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  908): releaseWL(44108508): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4677 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,D/PMS     (  908): acquireWL(4416c0b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1997 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42f9d168): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 1997): Checkin interval check for package: unspecified last checkin: 1452271949049 min interval config: 0 actual interval: 53158
,I/CheckinService( 1997): Checking schedule, now: 1452272002216 next: 1452271979024
,I/CheckinService( 1997): active receiver: enabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1997, uid=10029, userID:0
,I/CheckinService( 1997): Preparing to send checkin request
,I/EventLogService( 1997): Accumulating logs since 1452271944854
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
,E/dalvikvm( 4596): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4596): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/CheckinRequestBuilder( 1997): Checkin reason type: 8 attempt count: 1
W/ContextImpl( 4677): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4596): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4596): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4596): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4596): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4596): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4596): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4596): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4596): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4596): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4596): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4596): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4596): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4596): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4596): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1997): Failed to find provider info for com.google.android.wearable.settings
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4596): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4596): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/ContextImpl( 4677): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4677): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4677): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4677): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4596): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,I/dalvikvm-heap( 4596): Grow heap (frag case) to 9.985MB for 39954-byte allocation
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (1997/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4596): Grow heap (frag case) to 10.061MB for 79892-byte allocation
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4677/10151)
,V/WebViewChromiumFactoryProvider( 4677): Binding Chromium to main looper Looper (main, tid 1) {4240b338}
,I/LibraryLoader( 4677): Expected native library version number "",actual native library version number ""
I/dalvikvm-heap( 4596): Grow heap (frag case) to 10.088MB for 28144-byte allocation
,I/chromium( 4677): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4677): Initializing chromium process, renderers=0
,D/PMS     (  908): acquireWL(42f920f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
,D/PMS     (  908): acquireWL(42f646d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
,E/AudioManagerAndroid( 4677): BLUETOOTH permission is missing!
D/PMS     (  908): releaseWL(42f920f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4677): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4677): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4677): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4677): Local Branch: 
I/Adreno-EGL( 4677): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4677): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4677):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4708 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4677): Starting up...
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4677/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4677/10151)
,W/dalvikvm( 4708): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4708): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/MultiDex( 4708): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4708): install
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/MultiDex( 4708): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/MultiDex( 4708): loading existing secondary dex files
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3632/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3632/10160)
,I/MultiDex( 4708): load found 3 secondary dex files
,D/Process (  908): killProcessQuiet, pid=4300
I/MultiDex( 4708): install done
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 4300:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  908): Recipient 4300
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
,W/dalvikvm( 4708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4708): VFY: unable to resolve instance field 36
,W/dalvikvm( 4708): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/dalvikvm-heap( 4596): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
,V/JNIHelp ( 4708): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2718/10021)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44b9dbf8 u0 ReceiverList{44b9db58 4596 com.facebook.katana/10027/u0 remote:43dbffb0}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44b9dbf8 u0 ReceiverList{44b9db58 4596 com.facebook.katana/10027/u0 remote:43dbffb0}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43a77bd0 u0 ReceiverList{43037f00 4596 com.facebook.katana/10027/u0 remote:43d38940}}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/PMS     (  908): acquireWL(44b0c6c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1316): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ProviderInstaller( 4708): Installed default security provider GmsCore_OpenSSL
D/PMS     (  908): releaseWL(44b0c6c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
D/MobileConnectivityChangeReceiver( 4647): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4647): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1316): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1316): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1316): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4677/10151)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3632/10160)
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3632/10160)
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1997, uid=10029, userID:0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4708): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4708): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4708): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4708): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4708): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/WVCdm   (  363): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  363): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  363): CdmEngine::OpenSession
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,I/WVCdm   (  363): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  363): CdmEngine::GenerateKeyRequest
,D/LocationInitializer( 1997): Restart initialization of location
,D/AuthorizationBluetoothService( 1364): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1364): Proximity feature is not enabled.
,E/MDM     ( 1221): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4708): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  908): acquireWL(42dde918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42dde918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/WVCdm   (  363): PrepareKeyRequest: nonce=194504778
,I/WVCdm   (  363): CdmEngine::CloseSession
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4708): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4708): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4708):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4708): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4708): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4708):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4708/10029)
,W/Settings( 4708): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  363): CdmEngine::OpenSession
,I/WVCdm   (  363): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  363): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  363): PrepareKeyRequest: nonce=2577099035
,I/WVCdm   (  363): CdmEngine::CloseSession
,I/Adreno-EGL( 4708): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4708): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4708): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4708): Local Branch: 
I/Adreno-EGL( 4708): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4708): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4708):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 1997): Classify the device as Phone.
,D/libc    ( 1997): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1997): [NET] getaddrinfo-,err=8
D/libc    ( 1997): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1997): [NET] getaddrinfo-, 1
D/libc    ( 1997): [NET] getaddrinfo_proxy+
,D/libc    (  356): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =412f +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 249
D/libc    (  356): [NET]res_nsend:resplen=84
D/libc    (  356): [NET]res_queryN: exit 3, ancount=2
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1997): [NET] getaddrinfo_proxy-, success
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    ( 1997): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1997): [NET] getaddrinfo-,err=8
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =6987 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4479): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4479): BLE is supported
I/jxcore-log( 4479): 
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  356): [NET]res_nsend:resplen=172
D/libc    (  356): [NET]res_queryN: exit 3, ancount=4
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/104.81.130.175
,D/libc    ( 1997): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1997): [NET] getaddrinfo-,err=8
,D/libc    ( 1997): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1997): [NET] getaddrinfo-,err=8
,I/CheckinTask( 1997): Sending checkin request (12201 bytes)
,D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC <<
,I/CheckinRequestBuilder( 1997): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 1997): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (1997/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=21 [23][5][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
,I/CheckinRequestBuilder( 1997): Classify the device as Phone.
,I/CheckinTask( 1997): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/AutoSetting( 1494): service - handleMessage() stop self
,I/CheckinService( 1997): Checking schedule, now: 1452272004877 next: 1452794941867
,I/CheckinService( 1997): active receiver: disabled
,D/AutoSetting( 1494): service - onDestroy() END
,D/AutoSetting( 1494): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4331
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1997, uid=10029, userID:0
,I/ActivityManager(  908): Killing 4331:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/CheckinService( 1997): Recording last checkin time for package unspecified as 1452272004897
D/PMS     (  908): releaseWL(4416c0b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1997/10029)
D/PMS     (  908): acquireWL(42f3ecb0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1364): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1364): [NET] getaddrinfo-, 1
,D/libc    ( 1364): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =95e3 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,W/fb4a(:<default>):UserScope( 4596): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4596): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 238
D/libc    (  356): [NET]res_nsend:resplen=79
D/libc    (  356): [NET]res_queryN: exit 3, ancount=2
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/wpa_supplicant( 1184): nl80211: survey data missing!
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
D/libc    ( 1364): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
I/ActivityManager(  908): Recipient 4331
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1364): [NET] getaddrinfo-,err=8
,D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/PMS     (  908): acquireWL(43d28118): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/PMS     (  908): releaseWL(42f3ecb0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1364/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/PMS     (  908): releaseWL(43d28118): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4596): Called registerBroadcastReceiver twice.
D/PMS     (  908): acquireWL(43d28338): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1364/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1364/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
D/PMS     (  908): releaseWL(43d28338): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4596/10027)
,D/PMS     (  908): acquireWL(441ce218): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4576 10154 null
,W/ContextImpl( 4576): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4576, uid=10154, userID:0
,D/PMS     (  908): releaseWL(441ce218): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4576): Conditions not met for autocaching.
I/MusicLeanback( 4576): Stop autocaching.
,W/ContextImpl( 4576): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  908): releaseWL(42f646d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=22 [9][2][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4677): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  908): killProcessQuiet, pid=4371
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  908): killProcessQuiet, pid=4347
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4371:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  908): Killing 4347:com.htc.backup/1000 (adj 15): empty #18
,I/ActivityManager(  908): Recipient 4371
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4347
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=3959
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3959:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3959
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,W/Prism.AllAppsManager( 1267): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4772 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsUpdated
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4772): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4772): MmsConfig.loadMmsSettings
,W/dalvikvm( 4772): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4772): VFY: unable to resolve instance field 36
,W/dalvikvm( 4772): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4772): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  908): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4795 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4772, uid=10111, userID:0
,D/MessageFrequencyProvider( 4795): onCreate
,V/GetPrviateResource( 4795): GetPrviateResource
,V/GetPrviateResource( 4795): GetPrviateResource
,W/Settings( 4772): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 4795): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4795): query uri: content://htc-mms-customization/mms-ua/ua_profile
,W/PackageManager(  908): Unable to load service info ResolveInfo{43a34910 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Babel   ( 4772): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4772): MmsConfig.loadFromDatabase
,I/ProviderInstaller( 4772): Installed default security provider GmsCore_OpenSSL
,E/Babel   ( 4772): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4772): MmsConfig.loadFromResources
,E/Babel   ( 4772): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4772): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4795): sense_version=6.0
,D/BTAccessoryUtil( 4795): createReceiver
,D/BTAccessoryUtil( 4795): registerReceiver return intent = null
D/MessageCustFlag( 4795): sku_id=99
,W/SystemReader( 4795): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4795): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4795): networkCode: 
,D/MessageCustFlag( 4795): sku_id=99
D/MmsConfig( 4795): SIE smsPri: null
,D/MmsConfig( 4795): networkCode: 
,D/HtcTelephonyCapability( 4795): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4795): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4795): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4795): Cannot find qct_8960_interface, use default value instead
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4772, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4772, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4772, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4772, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4772, uid=10111, userID:0
,D/PMS     (  908): acquireWL(44b78b70): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4772 10111 null
,I/[PluginManager]RegisterService( 1316): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1316): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(44b1baf0): PARTIAL_WAKE_LOCK  Icing 0x1 1997 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(44b1b520): PARTIAL_WAKE_LOCK  AsyncService 0x1 3632 10160 null
,D/PMS     (  908): releaseWL(44b1baf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(44b1b520): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  908): acquireWL(44b0c2b0): PARTIAL_WAKE_LOCK  Icing 0x1 1997 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(44b78b70): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 1997): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1997): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  908): Resuming delayed broadcast
,I/Icing   ( 1997): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  908): applying state to connected service
D/PMS     (  908): acquireWL(42e1cdc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42e1cdc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  908): applying state to connected service
,D/PMS     (  908): acquireWL(42d1f4d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42d1f4d8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428301f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(428301f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 570 ms] updated apps [took 570 ms] 
,I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@42498d10 +
,I/Prism.WidgetManager( 1267): onLoadItems() +
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,I/Icing   ( 1997): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,E/Prism.WidgetManager( 1267): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1267): onLoadItems() -
,I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@42498d10 -
,I/Icing   ( 1997): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(44b0c2b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1236): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1236): -- N1 =0
,D/PhoneApp( 1236): -- N2 =0
,D/PhoneApp( 1236): -- N3 =0
,D/Messaging( 4795): mNeedToUpdateDate2 start
,D/MmsConfig( 4795): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4795): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4795): 
D/MmsAsyncWorkHandler( 4795): HM tk = 20001
,D/ReportIndicatorCache( 4795): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4795): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@4240c4f8
,I/Messaging( 4795): mccmnc> 
D/DraftCache( 4795): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4795): [DraftCache/1] refresh
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4795): networkCode: 
,D/Messaging( 4795): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4795): sense_version=6.0
D/PhoneStorageUtil( 4795): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4795): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4795): createReceiver
,D/Jerry   ( 4795): start to preload cursor >>>>>>>
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1236): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
V/MmsProvider( 1236): Update uri=content://mms, match=0
,V/MmsProvider( 1236): selection=st=129 AND m_type!=134
,D/Messaging( 4795): mNeedToUpdateDate2: false
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1236): sku_id=99
,D/Messaging( 4795): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4795): TransactionService is going to be woken up.
,V/TransactionService( 4795): 1-Creating TransactionService
,D/DraftCache( 4795): [DraftCache/478] rebuildCache
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/Messaging( 4795): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MmsSmsV2Provider( 1236):  phoneType = -1
V/TransactionService( 4795): onStartCommand: 1
,D/MmsSystemEventReceiver( 4795): unRegisterForConnectionStateChanges
V/TransactionService( 4795): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4795): Loading previous transactions.
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/Jerry   ( 1236): URI_DRAFT
D/Messaging( 4795): ViewCache CreatePreload
,D/Messaging( 4795): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1236): device_type: 1
,D/Cust_MMSMS( 4795): _has_set_default_values_2=true
,D/TransactionService( 4795): Force set service start id to 1
V/TransactionService( 4795): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4795): unRegisterForConnectionStateChanges
D/DraftCache( 4795): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4795): [DraftCache/478] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4795): 
D/MmsAsyncWorkHandler( 4795): HM tk = 20002
,V/TransactionService( 4795): Destroying TransactionService
,D/TransactionService( 4795): stopSelfResult: true, mLastHandledServiceId: 1
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1236): sku_id=99
,D/MsgPreferenceUtils( 4795): def_index: 0
,V/TransactionService( 4795): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4795): globalIndex = 1
D/MsgPreferenceUtils( 4795): phone state: true
D/MsgPreferenceUtils( 4795): sd state: false
,D/MsgPreferenceUtils( 4795): vIndex = 0
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63,
,D/AccFlag ( 1236): sku_id=99
,D/PMS     (  908): acquireWL(44b75e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{445c49d0: PendingIntentRecord{42e25818 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123901, Int=0
,D/PMS     (  908): acquireWL(445c38c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(44b75e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=14 [7][1][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42fbaaa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42fbaaa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(445c38c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42f91cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/PMS     (  908): releaseWL(42f91cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43dbfee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(44a50600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(440aa768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1452272015169 tag=VacuumService
D/PMS     (  908): releaseWL(43dbfee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(44a50600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4300a950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/PMS     (  908): releaseWL(4300a950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43842f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/PMS     (  908): releaseWL(440aa768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(43842f90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(44590178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/PMS     (  908): releaseWL(44590178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(44589fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(44589fb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(43860c28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42f80a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42f80a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(44514338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43860c28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43c90238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/PMS     (  908): releaseWL(43c90238): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 11511 seconds from now (1452272015774)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =5930 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 111
D/libc    (  356): [NET]res_nsend:resplen=87
,D/libc    (  356): [NET]res_queryN: exit 3, ancount=2
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=18 [11][2][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(44514338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43d545c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/PMS     (  908): releaseWL(43d545c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43ca5130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/PMS     (  908): releaseWL(43ca5130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4772): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  908): killProcessQuiet, pid=4318
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4318:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4318
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43dfd980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43dfd980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42f0dd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{44aed000: PendingIntentRecord{42eebc08 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137260, Int=0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/PMS     (  908): releaseWL(42f0dd48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1316): service - mHandler: update timezone
,D/AutoSetting( 1494): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1494): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1494): service - onCreate()
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1494): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1494): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1494): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1494): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1494): service - mHandler: update timezone
,D/AutoSetting( 1494): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1494): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1494): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1494): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{42558fe0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  908): acquireWL(4305e8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  908): sending alarm PendingIntent{42dcd150: PendingIntentRecord{42bd9540 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141641, Int=0
D/PMS     (  908): acquireWL(43a8a448): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(4305e8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =bd46 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
,D/AutoSetting( 1316): service - mHandler: update timezone
,D/AutoSetting( 1494): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1494): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1494): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1494): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1494): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1494): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1494): service - mHandler: update timezone
D/DotMatrix( 1561): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1494): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1494): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1494): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1494): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1561): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  356): [NET]res_nsend:resplen=238
,D/libc    (  356): [NET]res_queryN: exit 3, ancount=10
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 1316): service - handleMessage() stop self
,D/AutoSetting( 1316): service - handleMessage() quit looper
,D/AutoSetting( 1316): service - onDestroy() END
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{425c45c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 4 11 4 11
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(43a8a448): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(445c67f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=148974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(445c67f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  908): killProcessQuiet, pid=4402
,I/ActivityManager(  908): Killing 4402:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4402
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(44a0afe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44a0afe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43acd998 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1494): service - handleMessage() stop self
,D/AutoSetting( 1494): service - onDestroy() END
,D/AutoSetting( 1494): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4417
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4417:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4417
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(42dbb2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10027}
,V/AlarmManager(  908): sending alarm PendingIntent{433e9ce0: PendingIntentRecord{441f35b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174235, Int=0
,D/PMS     (  908): releaseWL(42dbb2c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/ClearcutLoggerApiImpl( 1364): disconnect managed GoogleApiClient
,D/TelephonyReceiver( 1236): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(42f5ea60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(42f5ea60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(438b4330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=208975, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(438b4330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44a69e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44a69e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(438937e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(438937e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(449ad328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=268974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(449ad328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(435ca138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(435ca138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(432a18a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432a18a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(445b4778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=328974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(445b4778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43c9d150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c9d150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4479): Connected to the server!
I/jxcore-log( 4479): 
,I/chromium( 4479): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4479): --- start :testFindPeers.js---
I/jxcore-log( 4479): 
,I/jxcore-log( 4479): testFindPeers created [object Object]
I/jxcore-log( 4479): 
,I/jxcore-log( 4479): serverPort is 8876
I/jxcore-log( 4479): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4479): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4479): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4479): start: Peer ID: B4:CE:F6:AB:A4:6A, peer name: HTC Desire 820
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4479): bind: Binding a new listener
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4479): initialize: My bluetooth address is B4:CE:F6:AB:A4:6A
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4479): verifyIdentityString: Identity string created: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC Desire 820"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4479): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 4479): getBluetoothService(): entry
,W/BluetoothAdapter( 4479): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1601): SOCK FLAG = 0 ***********************
,I/bt-btif ( 1601): BTA_JvCreateRecordByUser
D/bt-btm  ( 1601): BTM_AllocateSCN
D/bt-sdp  ( 1601): SDP_CreateRecord ok, num_records:17
,I/bt-btif ( 1601): BTA_JvRfcommStartServer
I/bt-btm  ( 1601): BTM_SEC_REG[19]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
,I/bt-btm  ( 1601):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4479): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 4479): start: OK
,I/io.jxcore.node.ConnectionHelper( 4479): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4479): start: Peer ID: B4:CE:F6:AB:A4:6A, peer name: HTC Desire 820
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4479): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 4479): bind: Binding a new listener
,W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 4479): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
,W/dalvikvm( 4479): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
E/dalvikvm( 4479): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 4479): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4479): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,W/dalvikvm( 4479): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 4479): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 4479): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/dalvikvm( 4479): threadid=1: thread exiting with uncaught exception (group=0x41fd5e30)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at android.os.Looper.loop(Looper.java:157)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): 	at dalvik.system.NativeStart.main(Native Method)
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(43a7e828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43a7e828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(4392c950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=388975, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4392c950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43d50120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43d50120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4466e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=448974, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4466e5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(449dd8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(449dd8b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/bt-btm  ( 1601): btm_dev_support_switch return FALSE
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
I/bt-btm  ( 1601): btm_sec_alloc_dev
I/bt-btm  ( 1601): BTM_InqDbRead: bd addr [583f547364c0]
D/bt-btm  ( 1601): BTM_GetHCIConnHandle
E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock Aquired
,D/PMS     (  908): acquireWL(43d1f248): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
D/bt-btm  ( 1601): btm_acl_resubmit_page
D/bt-btm  ( 1601): btm_acl_created hci_handle=1 link_role=1  is_le_link=0
D/bt-btm  ( 1601): device_type=0x0
D/bt-btm  ( 1601): btm_read_remote_features() handle: 1
D/bt-btm  ( 1601): btm_handle_to_acl_index
D/bt-btm  ( 1601): is_originator:0 
I/bt-btm  ( 1601): btm_sec_execute_procedure: Required:0x0 Flags:0x80 State:0
I/bt-btm  ( 1601): Security Manager: Start get name
D/bt-btm  ( 1601): btm_acl_paging discing:0, paging:0 BDA: 583f547364c0
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_acl_update_busy_level
D/bt-btm  ( 1601): BTM_BLI_PAGE_DONE_EVT
D/bt-btm  ( 1601): btm_acl_created hci_handle=1 link_role=1  is_le_link=0
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): Duplicate btm_acl_created: RemBdAddr: 583f547364c0
D/bt-btm  ( 1601): BTM_SetLinkPolicy
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_SetLinkSuperTout
D/bt-btm  ( 1601): btm_process_clk_off_comp_evt
D/bt-btm  ( 1601): btm_handle_to_acl_index
I/bt-btm  ( 1601): BTM_InqDbRead: bd addr [583f547364c0]
,D/bt-btm  ( 1601): btm_proc_lsto_evt
,D/bt-btm  ( 1601): btm_read_remote_version_complete
D/bt-btm  ( 1601): btm_read_remote_features_complete
D/bt-btm  ( 1601): btm_handle_to_acl_index
D/bt-btm  ( 1601): Start reading remote extended features
D/bt-btm  ( 1601): btm_read_remote_ext_features() handle: 1 page: 1
,I/bt-btm  ( 1601): BDA 58:3f:54:73:64:c0
I/bt-btm  ( 1601): Inquire BDA 00:00:00:00:00:00
I/bt-btm  ( 1601): btm_sec_rmt_name_request_complete
D/bt-btm  ( 1601): btm_bda_to_acl found
I/bt-btm  ( 1601): setting BTM_SEC_NAME_KNOWN sec_flags:0x88
I/bt-btm  ( 1601): btm_sec_execute_procedure: Required:0x0 Flags:0x88 State:0
I/bt-btm  ( 1601): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1601): Security Manager: access granted
D/bt-btm  ( 1601): btm_read_remote_ext_features_complete
D/bt-btm  ( 1601): btm_handle_to_acl_index
D/bt-btm  ( 1601): BTM reads next remote extended features page (2)
,D/bt-btm  ( 1601): btm_read_remote_ext_features() handle: 1 page: 2
,D/bt-btm  ( 1601): btm_read_remote_ext_features_complete
D/bt-btm  ( 1601): btm_handle_to_acl_index
D/bt-btm  ( 1601): BTM reached last remote extended features page (2)
D/bt-btm  ( 1601): btm_process_remote_ext_features
I/bt-btm  ( 1601): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
D/bt-btm  ( 1601): btm_establish_continue
D/bt-btm  ( 1601): btm_set_packet_types
,D/bt-btm  ( 1601): SetPacketType Mask -> 0xcc18
D/bt-btm  ( 1601): BTM_SetLinkPolicy
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
D/bt-btm  ( 1601): btm_acl_update_busy_level
D/bt-btm  ( 1601): BTM_BLI_ACL_UP_EVT
,D/bt-att  ( 1601): GATT   ATT protocol channel with BDA: 583f547364c0 is connected
D/bt-att  ( 1601): gatt_is_bda_in_the_srv_chg_clt_list :58-3f-54-73-64-c0
D/bt-btm  ( 1601): btm_sec_is_a_bonded_dev is_bonded=0
D/bt-att  ( 1601): connected is TRUE reason=0
,I/bt-smp  ( 1601): SMDBG l2c smp_connect_cback 
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,W/bt-btif ( 1601): info:x10
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214cc38
I/bt-btm  ( 1601): btm_find_or_alloc_dev
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x40
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
,I/bt-btif ( 1601): HAL bt_hal_cbacks->acl_state_changed_cb
,E/BluetoothRemoteDevices( 1601): aclStateChangeCallback: Device is NULL
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_get_max_packet_size
,I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x40
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x40  Result: 0
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc, CID: 0x40
,D/bt-sdp  ( 1601): releasing SDP rsp_list
,I/bt-btm  ( 1601): btm_find_or_alloc_dev
,I/bt-btm  ( 1601): btm_sec_change_pairing_state  Old: 0
I/bt-btm  ( 1601): btm_sec_change_pairing_state  New: 8 pairing_flags:0x0
D/bt-btm  ( 1601): btm_io_capabilities_rsp : rmt_io_caps is 0 
,I/bt-btm  ( 1601): btm_io_capabilities_req() State: 8
I/bt-btm  ( 1601): btm_find_or_alloc_dev
I/bt-btm  ( 1601): btm_io_capabilities_req() State: 8  Flags: 0x0000  p_cur_service: 0x00000000
I/bt-btm  ( 1601): btm_sec_change_pairing_state  Old: 8
I/bt-btm  ( 1601): btm_sec_change_pairing_state  New: 7 pairing_flags:0x0
,I/bt-btm  ( 1601): btm_io_capabilities_req: State: 7  IO_CAP:1 oob_data:0 auth_req:0
,I/bt-btm  ( 1601): btm_proc_sp_req_evt() BDA: 583f547364c0 event: 0x2, State: 7
I/bt-btm  ( 1601): btm_sec_change_pairing_state  Old: 7
I/bt-btm  ( 1601): btm_sec_change_pairing_state  New: 4 pairing_flags:0x0
D/bt-btm  ( 1601): btm_proc_sp_req_evt()  just_works:1, io loc:1, rmt:1, auth loc:0, rmt:0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->remote_device_properties_cb
,D/BluetoothRemoteDevices( 1601): Remote class is:5898764
,I/bt-btif ( 1601): HAL bt_hal_cbacks->bond_state_changed_cb
I/BluetoothBondStateMachine( 1601): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 1601): check_cod: remote_cod = 0x5a020c
I/bt-btm  ( 1601): BTM_ConfirmReqReply() State: 4  Res: 0
I/bt-btm  ( 1601): btm_sec_change_pairing_state  Old: 4
,I/bt-btm  ( 1601): btm_sec_change_pairing_state  New: 9 pairing_flags:0x0
I/BluetoothBondStateMachine( 1601): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 1601): Entering PendingCommandState State
,V/BluetoothSapReceiver( 1601): SapReceiver onReceive 
D/BluetoothAdapter( 1741): getBluetoothService(): entry
V/BluetoothSapReceiver( 1601): action = android.bluetooth.device.action.BOND_STATE_CHANGED
D/BluetoothAdapter( 1741): getBluetoothService(): callingUser = 0 callingUid = 1002 callingAppId = 1002
D/BluetoothAdapter( 1741): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@424831c0
D/BluetoothDevice( 1741): getService : Register callback
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1741): isLeDevice: 58:3F:54:73:64:C0
,V/BluetoothSapReceiver( 1601): Calling SAP service start service with action = android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapService( 1601): action: android.bluetooth.device.action.BOND_STATE_CHANGED
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
V/BluetoothSapService( 1601): state: -2147483648
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@446416d0:true
D/BluetoothAdapter( 3849): getBluetoothService(): entry
D/BluetoothAdapter( 3849): getBluetoothService(): callingUser = 0 callingUid = 1000 callingAppId = 1000
D/BluetoothAdapter( 3849): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@425b3e40
,D/BluetoothDevice( 3849): getService : Register callback
,I/bt-btm  ( 1601): btm_simple_pair_complete()  Pair State: 9  Status:0  sec_state: 0
,I/bt-btm  ( 1601): btm_find_or_alloc_dev
,I/bt-btm  ( 1601): btm_sec_link_key_notification()  BDA:583f547364c0, TYPE: 4
I/bt-btm  ( 1601): btm_sec_change_pairing_state  Old: 9
I/bt-btm  ( 1601): btm_sec_change_pairing_state  New: 0 pairing_flags:0x0
I/bt-btm  ( 1601): BTM_IsInquiryActive
,I/bt-btm  ( 1601): BTM_IsRNRActive
I/bt-btm  ( 1601): BTM_InqDbRead: bd addr [583f547364c0]
I/bt-btm  ( 1601): BTM_ReadRemoteDeviceName: bd addr [583f547364c0]
I/bt-btm  ( 1601): no device found in inquiry db
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_acl_paging discing:0, paging:0 BDA: 583f547364c0
,D/bt-btm  ( 1601): btm_bda_to_acl found
,I/bt-btm  ( 1601): BDA 58:3f:54:73:64:c0
,I/bt-btm  ( 1601): Inquire BDA 58:3f:54:73:64:c0
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_bda_to_acl found
I/bt-btm  ( 1601): btm_sec_rmt_name_request_complete
D/bt-btm  ( 1601): btm_bda_to_acl found
I/bt-btm  ( 1601): setting BTM_SEC_NAME_KNOWN sec_flags:0xba
,I/bt-btm  ( 1601): BTM_InqDbRead: bd addr [583f547364c0]
I/bt-btm  ( 1601): BTM_IsAclConnectionUp: RemBdAddr: 583f547364c0
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_bda_to_acl found
E/bt-btif ( 1601): services_to_search = 3fffffff
,E/bt-btif ( 1601): ****************search UUID = 1200***********
I/bt-sdp  ( 1601): SDP - Originate started
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:1, 0x6214cd94
,I/bt-btm  ( 1601): btm_find_or_alloc_dev
,D/bt-btm  ( 1601): btm_acl_encrypt_change handle=1 status=0 encr_enabl=1
D/bt-btm  ( 1601): btm_handle_to_acl_index
I/bt-btm  ( 1601): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
D/bt-btm  ( 1601): before update p_dev_rec->sec_flags=0xba
D/bt-btm  ( 1601): after update p_dev_rec->sec_flags=0xbe
,D/bt-btm  ( 1601): btm_bda_to_acl found
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214cef0
I/bt-btm  ( 1601): btm_find_or_alloc_dev
D/bt-btm  ( 1601): btm_sec_l2cap_access_req()  sm4:0x11, sec_flags:0xbe, security_required:0x86 chk:1
D/bt-btm  ( 1601): no next_serv sm4:0x11, chk:1
D/bt-btm  ( 1601): (SM4 to SM4) btm_sec_l2cap_access_req rspd. authenticated: x2, enc: x4
D/bt-btm  ( 1601): btm_sec_check_upgrade...
D/bt-btm  ( 1601): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
D/bt-btm  ( 1601): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
I/bt-btm  ( 1601): Security Manager: l2cap_access_req PSM:3 Handle:1 State:0 Flags:0xbe Required:0x86 Service ID:42
I/bt-btm  ( 1601): btm_sec_execute_procedure: Required:0x86 Flags:0xbe State:0
I/bt-btm  ( 1601): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1601): Security Manager: access granted
,I/bt-sdp  ( 1601): SDP - got conn cnf, sent cfg req, CID: 0x41
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_get_max_packet_size
I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x41
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_get_max_packet_size
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x41  Result: 0
,W/bt-sdp  ( 1601): process_service_search_attr_rsp
,I/bt-sdp  ( 1601): SDP - disconnect  CID: 0x41
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:1, min:0
,I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc cfm, CID: 0x41
D/bt-sdp  ( 1601): releasing SDP rsp_list
E/bt-btif ( 1601): services_to_search = 3ffffffe
E/bt-btif ( 1601): ****************search UUID = 0100***********
I/bt-sdp  ( 1601): SDP - Originate started
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:1, 0x6214d04c
,I/bt-btm  ( 1601): btm_find_or_alloc_dev
D/bt-btm  ( 1601): btm_sec_mx_access_request is_originator:0
I/bt-btm  ( 1601): btm_find_or_alloc_dev
D/bt-btm  ( 1601): btm_sec_find_mx_serv
D/bt-btm  ( 1601): btm_sec_check_upgrade...
D/bt-btm  ( 1601): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
D/bt-btm  ( 1601): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
I/bt-btm  ( 1601): Security Manager: mx_access_req proto_id:3 chan_id:4 State:0 Flags:0xbe Required:0x80 Service ID:58
I/bt-btm  ( 1601): btm_sec_execute_procedure: Required:0x80 Flags:0xbe State:0
I/bt-btm  ( 1601): Security Manager: trusted:0x00000000
I/bt-btm  ( 1601): Security Manager: access granted
I/bt-btif ( 1601): BTA_JVSetPmProfile handle:0x87, app_id:255
I/bt-btif ( 1601): bta_jv_set_pm_profile(handle: 0x87, app_id: 255, init_st: 0)
I/bt-btif ( 1601): bta_jv_alloc_set_pm_profile_cb(handle 0x87, app_id 255): idx: 0, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x62152a4c
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 0)
W/bt-btif ( 1601): new conn_srvc id:26, app_id:255
W/bt-btif ( 1601): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1601): bta_dm_pm_ssr:2, lat:1200
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/BluetoothAdapter( 4479): getBluetoothService(): entry
I/bt-sdp  ( 1601): SDP - got conn cnf, sent cfg req, CID: 0x43
D/BluetoothAdapter( 4479): getBluetoothService(): callingUser = 0 callingUid = 10389 callingAppId = 10389
D/BluetoothAdapter( 4479): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@42f531f0
D/BluetoothDevice( 4479): getService : Register callback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Incoming connection initialized (thread ID: 468)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4479): Entering thread (ID: 468)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_get_max_packet_size
,I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x43
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x43  Result: 0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): onBytesRead: Read 63 bytes successfully (thread ID: 468)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Got valid identity from [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): onBytesWritten: 73 bytes successfully written (thread ID: 468)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): removeThreadFromList: Removing thread with ID 468
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Handshake thread disposed (thread ID: 468)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): onIncomingConnectionConnected: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4479): Exiting thread (ID: 468)
I/bt-btif ( 1601): BTA_JvRfcommWrite
I/bt-btif ( 1601): write ok
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,W/bt-sdp  ( 1601): process_service_search_attr_rsp
,I/bt-sdp  ( 1601): SDP - disconnect  CID: 0x43
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:1, min:0
,I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc cfm, CID: 0x43
,D/bt-sdp  ( 1601): releasing SDP rsp_list
,E/bt-btif ( 1601): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 1601): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 1601): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/bt-btif ( 1601): HAL bt_hal_cbacks->bond_state_changed_cb
,I/BluetoothBondStateMachine( 1601): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
I/bt-btif ( 1601): HAL bt_hal_cbacks->remote_device_properties_cb
,D/BluetoothAdapterProperties( 1601): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 1601): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,V/BluetoothSapReceiver( 1601): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1601): action = android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapReceiver( 1601): Calling SAP service start service with action = android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1741): isLeDevice: 58:3F:54:73:64:C0
V/BluetoothSapService( 1601): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothSapService( 1601): state: -2147483648
,I/BluetoothBondStateMachine( 1601): StableState(): Entering Off State
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
E/bt-btif ( 1601): send none, EAGAIN or EWOULDBLOCK, errno:11
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x87, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,W/bt-btif ( 1601): dm_pm_timer expires
,W/bt-btif ( 1601): dm_pm_timer expires 0
,W/bt-btif ( 1601): proc dm_pm_timer expires
W/bt-btif ( 1601): BTA_DM_PM_SNIFF
,W/bt-btif ( 1601): check RemoteVersion
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteVersion
W/bt-btif ( 1601): lmp_version = 6, manufacturer = 29, lmp_sub_version= 2003
,W/bt-btif ( 1601): enable sniff
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x2
,D/bt-btm  ( 1601): btm_handle_to_acl_index
,D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
,D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1601): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock released
D/PMS     (  908): releaseWL(43d1f248): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,I/bt-btif ( 1601): BTA_JvRfcommClose
I/bt-btif ( 1601): bta_jv_free_set_pm_profile_cb(jv_handle: 0x87), idx: 0, app_id: 0xff
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
W/bt-btif ( 1601): invalid rfc slot id: 7
E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock Aquired
D/PMS     (  908): acquireWL(4458f450): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock released
D/PMS     (  908): releaseWL(4458f450): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/bt-btm  ( 1601): btm_handle_to_acl_index
,D/bt-btm  ( 1601): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0001, p->state 0x00
,D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,W/bt-rfcomm( 1601): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 1601): RFCOMM_DisconnectInd LCID:0x42
E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock Aquired
D/PMS     (  908): acquireWL(42d74c40): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
,D/PMS     (  908): acquireWL(43a84170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43a84170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,I/bt-btm  ( 1601): btm_sec_send_hci_disconnect:  handle:0x1, reason=0x13
,D/bt-att  ( 1601): GATT   ATT protocol channel with BDA: 583f547364c0 is disconnected
,D/bt-att  ( 1601): gatt_is_bda_in_the_srv_chg_clt_list :58-3f-54-73-64-c0
D/bt-btm  ( 1601): btm_sec_is_a_bonded_dev is_bonded=1
D/bt-att  ( 1601): gatt_add_srv_chg_clt
D/bt-att  ( 1601): enqueue a srv chg client
D/bt-att  ( 1601): gatt_cleanup_upon_disc 
,D/bt-att  ( 1601): exit gatt_cleanup_upon_disc 
D/bt-att  ( 1601): ATT disconnected
I/bt-smp  ( 1601): SMDBG l2c smp_connect_cback 
D/bt-btm  ( 1601): btm_acl_removed
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_acl_report_role_change
D/bt-btm  ( 1601): btm_acl_update_busy_level
,D/bt-btm  ( 1601): BTM_BLI_ACL_DOWN_EVT
D/bt-btm  ( 1601): acl hci_handle=1 is_le_link=0 connectable_mode=0x0 link_role=1
D/bt-btm  ( 1601): before update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1601): Bletooth link down
D/bt-btm  ( 1601): after update p_dev_rec->sec_flags=0xb8
,D/bt-btm  ( 1601): btm_acl_resubmit_page
E/bt-btm  ( 1601): btm_sec_disconnected - Clearing Pending flag
I/bt-btm  ( 1601): before Update sec_flags=0xb8
D/bt-btm  ( 1601): btm_ble_update_mode_operation adv_mode = 0
,I/bt-btm  ( 1601): after Update sec_flags=0xb8
D/bt-btm  ( 1601): btm_get_acl_disc_reason_code
,I/bt-btif ( 1601): HAL bt_hal_cbacks->acl_state_changed_cb
,D/BluetoothAdapterService(1111630976)( 1601): Get ACL Connected Devices being called
E/BluetoothAdapterProperties( 1601): setAclConnectedDevices failed to remove device: 58:3F:54:73:64:C0
,D/BluetoothRemoteDevices( 1601): aclStateChangeCallback: State:DisConnected to Device:58:3F:54:73:64:C0
,V/BluetoothSapReceiver( 1601): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1601): action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapReceiver( 1601): Calling SAP service start service with action = android.bluetooth.device.action.ACL_DISCONNECTED
D/BluetoothAdapter( 1221): getBluetoothService(): entry
D/BluetoothAdapter( 1221): getBluetoothService(): callingUser = 0 callingUid = 10029 callingAppId = 10029
D/BluetoothAdapter( 1221): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@423faf70
,D/BluetoothDevice( 1221): getService : Register callback
V/BluetoothSapService( 1601): action: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapService( 1601): state: -2147483648
,W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f06780:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  908): acquireWL(43d24f28): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1221 10029 null
D/BluetoothAdapter( 2856): getBluetoothService(): entry
D/BluetoothAdapter( 2856): getBluetoothService(): callingUser = 0 callingUid = 10086 callingAppId = 10086
D/BluetoothAdapter( 2856): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@427df328
D/BluetoothDevice( 2856): getService : Register callback
E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 2856): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 2856): getBluetoothClass(): COD is 5898764
,I/BTConnectionReceiver( 2856): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2856): Bluetooth Device Name: G3-1
,E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 1221): 1114880472: getState(). Returning 12
D/BluetoothAdapterService(1111630976)( 1601): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1601): getBondedDevices: length=10
,D/BluetoothAdapter( 1221): 1114880472: getState(). Returning 12
D/BluetoothAdapterService(1111630976)( 1601): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1601): getBondedDevices: length=10
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock released
D/PMS     (  908): releaseWL(43d24f28): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  908): releaseWL(42d74c40): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/bt-btm  ( 1601): btm_dev_support_switch return TRUE (feature found)
,W/bt-l2cap( 1601): l2cu_get_conn_role 1
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/PMS     (  908): acquireWL(43529570): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
D/BluetoothRemoteDevices( 1601): Wake lock Aquired
,D/bt-btm  ( 1601): btm_acl_resubmit_page
,D/bt-btm  ( 1601): btm_acl_created hci_handle=2 link_role=1  is_le_link=0
D/bt-btm  ( 1601): device_type=0x0
D/bt-btm  ( 1601): btm_establish_continue
,D/bt-btm  ( 1601): btm_set_packet_types
D/bt-btm  ( 1601): SetPacketType Mask -> 0xcc18
D/bt-btm  ( 1601): BTM_SetLinkPolicy
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
D/bt-btm  ( 1601): btm_acl_update_busy_level
D/bt-btm  ( 1601): BTM_BLI_ACL_UP_EVT
,D/bt-btm  ( 1601): is_originator:0 
D/bt-btm  ( 1601): btm_acl_update_busy_level
D/bt-btm  ( 1601): BTM_BLI_PAGE_DONE_EVT
,D/bt-btm  ( 1601): btm_acl_created hci_handle=2 link_role=1  is_le_link=0
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): Duplicate btm_acl_created: RemBdAddr: 583f547364c0
,D/bt-btm  ( 1601): BTM_SetLinkPolicy
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_SetLinkSuperTout
D/bt-btm  ( 1601): btm_process_clk_off_comp_evt
,D/bt-btm  ( 1601): btm_handle_to_acl_index
I/bt-btm  ( 1601): BTM_InqDbRead: bd addr [583f547364c0]
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
W/bt-btif ( 1601): info:x10
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
,I/bt-btif ( 1601): HAL bt_hal_cbacks->acl_state_changed_cb
,D/BluetoothAdapterService(1111630976)( 1601): Get ACL Connected Devices being called
I/BluetoothAdapterProperties( 1601): Adding ACL connected device: 58:3F:54:73:64:C0
,D/BluetoothRemoteDevices( 1601): aclStateChangeCallback: State:Connected to Device:58:3F:54:73:64:C0
,D/PMS     (  908): acquireWL(44439458): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1221 10029 null
,I/ActivityManager(  908): Start proc com.futuredial for broadcast com.futuredial/.fdbtserver.BTServiceReceiver: pid=4885 uid=10084 gids={50084, 3002, 3001}
E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
D/bt-btm  ( 1601): btm_proc_lsto_evt
D/bt-btm  ( 1601): btm_read_remote_version_complete
E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,D/bt-att  ( 1601): GATT   ATT protocol channel with BDA: 583f547364c0 is connected
,D/bt-att  ( 1601): gatt_is_bda_in_the_srv_chg_clt_list :58-3f-54-73-64-c0
D/bt-att  ( 1601): bda is in the srv chg clt list
D/bt-att  ( 1601): connected is TRUE reason=0
,I/bt-smp  ( 1601): SMDBG l2c smp_connect_cback 
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214d1a8
I/bt-btm  ( 1601): btm_find_or_alloc_dev
,I/bt-sdp  ( 1601): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x44
,D/BluetoothAdapter( 1221): 1114880472: getState(). Returning 12
D/BluetoothAdapterService(1111630976)( 1601): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1601): getBondedDevices: length=10
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_get_max_packet_size
,I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x44
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x44  Result: 0
,D/BluetoothAdapter( 1221): 1114880472: getState(). Returning 12
,D/BluetoothAdapterService(1111630976)( 1601): Get Bonded Devices being called
D/BluetoothAdapterProperties( 1601): getBondedDevices: length=10
,D/[FDDMI]BTServiceReceiver( 4885): android.bluetooth.device.action.ACL_CONNECTED
,D/PMS     (  908): releaseWL(44439458): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc, CID: 0x44
D/bt-sdp  ( 1601): releasing SDP rsp_list
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f9d850:true
D/BluetoothAdapter( 4885): getBluetoothService(): entry
D/BluetoothAdapter( 4885): getBluetoothService(): callingUser = 0 callingUid = 10084 callingAppId = 10084
D/BluetoothAdapter( 4885): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@42411848
D/BluetoothDevice( 4885): getService : Register callback
I/[FDDMI]BTServiceReceiver( 4885): startService is true
,I/ActivityManager(  908): Start proc com.futuredial:FdbtService for service com.futuredial/.fdbtserver.FdbtService: pid=4897 uid=10084 gids={50084, 3002, 3001}
,I/bt-btm  ( 1601): btm_find_or_alloc_dev
I/bt-btm  ( 1601): btm_sec_link_key_request()  BDA: 58:3f:54:73:64:c0
,D/Process (  908): killProcessQuiet, pid=4449
,I/ActivityManager(  908): Killing 4449:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/BluetoothDevice( 2856): getBluetoothClass(): COD is 5898764
I/ActivityManager(  908): Recipient 4449
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/BluetoothDevice( 2856): getBluetoothClass(): COD is 5898764
,I/BTConnectionReceiver( 2856): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2856): Bluetooth Device Name: G3-1
,E/[FDDMI]FDBTService( 4897): enter function onCreate
,W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4305de68:true
,W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
,E/[FDDMI]FDBTService( 4897): mHasStarted value is false
D/bt-btm  ( 1601): btm_acl_encrypt_change handle=2 status=0 encr_enabl=1
,D/bt-btm  ( 1601): btm_handle_to_acl_index
D/BluetoothAdapter( 4897): 1111560920: getState(). Returning 12
E/[FDDMI]FDBTService( 4897): state is 12
I/bt-btm  ( 1601): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
E/[FDDMI]FDBTService( 4897): InitForegroundMethods
D/bt-btm  ( 1601): before update p_dev_rec->sec_flags=0xb8
E/[FDDMI]FDBTService( 4897): exit function onCreate
D/bt-btm  ( 1601): after update p_dev_rec->sec_flags=0xbe
,D/bt-btm  ( 1601): btm_bda_to_acl found
I/[FDDMI]FDBTService( 4897): enter function onStartCommand
,I/[FDDMI]FDBTService( 4897): retCode is 1
D/[FDDMI]FDBTService( 4897): Binder_2 has same Thread!
D/[FDDMI]FDBTService( 4897): Binder_1 has same Thread!
D/[FDDMI]FDBTService( 4897): main has same Thread!
I/[FDDMI]FDBTService( 4897): startId is 1
D/BluetoothAdapter( 4897): 1111560920: getState(). Returning 12
I/[FDDMI]FDBTService( 4897): start to parse intent
,I/[FDDMI]FDBTService( 4897): enter function parseIntent
D/BluetoothAdapter( 4897): getBluetoothService(): entry
D/BluetoothAdapter( 4897): getBluetoothService(): callingUser = 0 callingUid = 10084 callingAppId = 10084
D/BluetoothAdapter( 4897): getBluetoothService: cb = android.bluetooth.BluetoothDevice$1@42415518
D/BluetoothDevice( 4897): getService : Register callback
I/[FDDMI]FDBTService( 4897): action is android.bluetooth.device.action.ACL_CONNECTED
I/[FDDMI]FDBTService( 4897): exit function parseIntent
,I/[FDDMI]FDBTService( 4897): exit function onStartCommand, retCode is 1
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214d304
I/bt-btm  ( 1601): btm_find_or_alloc_dev
,D/bt-btm  ( 1601): btm_sec_l2cap_access_req()  sm4:0x11, sec_flags:0xbe, security_required:0x86 chk:1
D/bt-btm  ( 1601): no next_serv sm4:0x11, chk:1
D/bt-btm  ( 1601): (SM4 to SM4) btm_sec_l2cap_access_req rspd. authenticated: x2, enc: x4
D/bt-btm  ( 1601): btm_sec_check_upgrade...
,D/bt-btm  ( 1601): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
D/bt-btm  ( 1601): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
I/bt-btm  ( 1601): Security Manager: l2cap_access_req PSM:3 Handle:2 State:0 Flags:0xbe Required:0x86 Service ID:42
,I/bt-btm  ( 1601): btm_sec_execute_procedure: Required:0x86 Flags:0xbe State:0
I/bt-btm  ( 1601): Security Manager: trusted:0x00000000
,I/bt-btm  ( 1601): Security Manager: access granted
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_get_max_packet_size
,D/bt-btm  ( 1601): btm_sec_mx_access_request is_originator:0
,I/bt-btm  ( 1601): btm_find_or_alloc_dev
D/bt-btm  ( 1601): btm_sec_find_mx_serv
D/bt-btm  ( 1601): btm_sec_check_upgrade...
,D/bt-btm  ( 1601): btm_sec_is_upgrade_possible link_key_typet:4, rmt_io_caps:1, chk flags:x1000
D/bt-btm  ( 1601): btm_sec_is_upgrade_possible is_possible:0 sec_flags:0xbe
I/bt-btm  ( 1601): Security Manager: mx_access_req proto_id:3 chan_id:4 State:0 Flags:0xbe Required:0x80 Service ID:58
,I/bt-btm  ( 1601): btm_sec_execute_procedure: Required:0x80 Flags:0xbe State:0
I/bt-btm  ( 1601): Security Manager: trusted:0x00000000
I/bt-btm  ( 1601): Security Manager: access granted
,I/bt-btif ( 1601): BTA_JVSetPmProfile handle:0x187, app_id:255
,I/bt-btif ( 1601): bta_jv_set_pm_profile(handle: 0x187, app_id: 255, init_st: 0)
I/bt-btif ( 1601): bta_jv_alloc_set_pm_profile_cb(handle 0x187, app_id 255): idx: 0, (BTA_JV_PM_MAX_NUM: 5), pp_cb: 0x62152a60
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Incoming connection accepted
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 0)
W/bt-btif ( 1601): new conn_srvc id:26, app_id:255
W/bt-btif ( 1601): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 1601): bta_dm_pm_ssr:2, lat:1200
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4479): Entering thread (ID: 469)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Incoming connection initialized (thread ID: 469)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Waiting for incoming connections...
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): onBytesRead: Read 63 bytes successfully (thread ID: 469)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Got valid identity from [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): onBytesWritten: 73 bytes successfully written (thread ID: 469)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): removeThreadFromList: Removing thread with ID 469
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 4479): Handshake thread disposed (thread ID: 469)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4479): onIncomingConnectionConnected: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 4479): Exiting thread (ID: 469)
I/bt-btif ( 1601): BTA_JvRfcommWrite
I/bt-btif ( 1601): write ok
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
V/[FDDMI]FDBTService( 4897): Handler(): got msg=1
I/[FDDMI]FDBTService( 4897): receive msg: START_LISTENER
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
I/[FDDMI]FDBTService( 4897): bluetooth adapter is enbaled
I/[FDDMI]FDBTService( 4897): enter function startRfcommSocketListener
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/[FDDMI]FDBTService( 4897): exit function startRfcommSocketListener
I/[FDDMI]FDBTService( 4897): naname thread start here
I/[FDDMI]FDBTService( 4897): exit handleMessage
V/[FDDMI]FDBTService( 4897): Service startRfcommSocketListener
I/[FDDMI]FDBTService( 4897): enter function startTimeOut
I/[FDDMI]FDBTService( 4897): exit function startTimeOut
I/[FDDMI]FDBTService( 4897): mServerSocket is null
I/[FDDMI]FDBTService( 4897): enter function initSocket
V/[FDDMI]FDBTService( 4897): FD bluetooth Service initSocket
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
I/[FDDMI]FDBTService( 4897): start to bind DMI service to DMIBTUUID 
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
D/BluetoothAdapter( 4897): getBluetoothService(): entry
W/BluetoothAdapter( 4897): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1601): SOCK FLAG = 3 ***********************
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): BTA_JvCreateRecordByUser
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
D/bt-btm  ( 1601): BTM_AllocateSCN
D/bt-sdp  ( 1601): SDP_CreateRecord ok, num_records:18
I/bt-btif ( 1601): BTA_JvRfcommStartServer
I/bt-btm  ( 1601): BTM_SEC_REG[20]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 1601):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
V/[FDDMI]FDBTService( 4897): FD listenUsingRfcommWithServiceRecord Service initSocket
I/[FDDMI]FDBTService( 4897): exit function initSocket, initSocketOK is true
V/[FDDMI]FDBTService( 4897): Service SocketAcceptThread
I/[FDDMI]FDBTService( 4897): mAcceptThread is null
I/[FDDMI]FDBTService( 4897): noname thread end here
I/[FDDMI]FDBTService( 4897): SocketAcceptTread start here
V/[FDDMI]FDBTService( 4897): Service SocketAcceptThread run
V/[FDDMI]FDBTService( 4897): Service mServerSocket.accept
E/[FDDMI]FDBTService( 4897): waiting for connection request from remote device
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
E/bt-btif ( 1601): send none, EAGAIN or EWOULDBLOCK, errno:11
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 1, app_id: 255, conn_state: 7)
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-btif ( 1601): bta_jv_pm_state_change(p_cb: 0x62152c00, handle: 0x187, busy/idle_state: 2, app_id: 255, conn_state: 6)
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
,W/bt-btif ( 1601): dm_pm_timer expires
,W/bt-btif ( 1601): dm_pm_timer expires 0
W/bt-btif ( 1601): proc dm_pm_timer expires
W/bt-btif ( 1601): BTA_DM_PM_SNIFF
,W/bt-btif ( 1601): check RemoteVersion
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
,W/bt-btif ( 1601): lmp_version = 6, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1601): enable sniff
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x2
,D/bt-btm  ( 1601): btm_handle_to_acl_index
,D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1601): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock released
D/PMS     (  908): releaseWL(43529570): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/PMS     (  908): acquireWL(43ca33d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=508974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43ca33d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{43a689a0 u0 com.futuredial/.fdbtserver.FdbtService}
,D/bt-btm  ( 1601): btm_handle_to_acl_index
D/bt-btm  ( 1601): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214d460
I/bt-btm  ( 1601): btm_find_or_alloc_dev
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x46
E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock Aquired
D/PMS     (  908): acquireWL(4462b910): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_get_max_packet_size
,I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x46
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x46  Result: 0
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc, CID: 0x46
,D/bt-sdp  ( 1601): releasing SDP rsp_list
,W/bt-btif ( 1601): dm_pm_timer expires
,W/bt-btif ( 1601): dm_pm_timer expires 0
W/bt-btif ( 1601): proc dm_pm_timer expires
W/bt-btif ( 1601): BTA_DM_PM_SNIFF
W/bt-btif ( 1601): check RemoteVersion
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
W/bt-btif ( 1601): lmp_version = 6, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1601): enable sniff
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x12
,D/bt-btm  ( 1601): btm_handle_to_acl_index
,D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1601): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock released
D/PMS     (  908): releaseWL(4462b910): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/bt-btm  ( 1601): btm_handle_to_acl_index
D/bt-btm  ( 1601): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214d5bc
I/bt-btm  ( 1601): btm_find_or_alloc_dev
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x47
E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock Aquired
D/PMS     (  908): acquireWL(4397d7e0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_get_max_packet_size
,I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x47
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x47  Result: 0
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc, CID: 0x47
,D/bt-sdp  ( 1601): releasing SDP rsp_list
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214d718
I/bt-btm  ( 1601): btm_find_or_alloc_dev
,I/bt-sdp  ( 1601): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x48
,D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): btm_get_max_packet_size
I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x48
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x48  Result: 0
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc, CID: 0x48
,D/bt-sdp  ( 1601): releasing SDP rsp_list
,W/bt-btif ( 1601): dm_pm_timer expires
,W/bt-btif ( 1601): dm_pm_timer expires 0
W/bt-btif ( 1601): proc dm_pm_timer expires
W/bt-btif ( 1601): BTA_DM_PM_SNIFF
W/bt-btif ( 1601): check RemoteVersion
D/bt-btm  ( 1601): btm_bda_to_acl found
,D/bt-btm  ( 1601): BTM_ReadRemoteVersion
W/bt-btif ( 1601): lmp_version = 6, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1601): enable sniff
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x12
,D/bt-btm  ( 1601): btm_handle_to_acl_index
,D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1601): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock released
D/PMS     (  908): releaseWL(4397d7e0): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/bt-btm  ( 1601): btm_handle_to_acl_index
,D/bt-btm  ( 1601): btm mode change to active; check l2c_link for outgoing packets
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
D/bt-btm  ( 1601): btm_sec_l2cap_access_req is_originator:0, 0x6214d874
,I/bt-btm  ( 1601): btm_find_or_alloc_dev
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP conn ind, sent config req, CID 0x49
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock Aquired
D/PMS     (  908): acquireWL(43c97d10): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
,D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_get_max_packet_size
,I/bt-sdp  ( 1601): SDP - Rcvd cfg ind, sent cfg cfm, CID: 0x49
,I/bt-sdp  ( 1601): SDP - Rcvd cfg cfm, CID: 0x49  Result: 0
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 128 BDA: 547364c0 mode:0x0
,D/bt-btm  ( 1601): BTM_SetPowerMode: mode:0x0 interval 0 max:0, min:0
I/bt-sdp  ( 1601): SDP - Rcvd L2CAP disc, CID: 0x49
,D/bt-sdp  ( 1601): releasing SDP rsp_list
,D/PMS     (  908): acquireWL(43e00190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43e00190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/bt-btif ( 1601): dm_pm_timer expires
,W/bt-btif ( 1601): dm_pm_timer expires 0
W/bt-btif ( 1601): proc dm_pm_timer expires
W/bt-btif ( 1601): BTA_DM_PM_SNIFF
W/bt-btif ( 1601): check RemoteVersion
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): BTM_ReadRemoteVersion
W/bt-btif ( 1601): lmp_version = 6, manufacturer = 29, lmp_sub_version= 2003
W/bt-btif ( 1601): enable sniff
,I/bt-btm  ( 1601): BTM_SetPowerMode: pm_id 0 BDA: 547364c0 mode:0x12
,D/bt-btm  ( 1601): btm_handle_to_acl_index
,D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_sco_disc_chk_pend_for_modechange: hci_handle 0x0002, p->state 0x00
D/bt-btm  ( 1601): btm_cont_rswitch_or_chglinkkey 
,W/bt-btif ( 1601): bta_dm_pm_btm_status  stopping timer if activesince sniff mode is enabled
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothRemoteDevices( 1601): Wake lock released
D/PMS     (  908): releaseWL(43c97d10): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/PMS     (  908): acquireWL(44a02338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=568974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44a02338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/bt-btif ( 1601): BTA_JvRfcommClose
W/bt-btif ( 1601): invalid rfc slot id: 8
D/bt-att  ( 1601): GATT   ATT protocol channel with BDA: 583f547364c0 is disconnected
D/bt-att  ( 1601): gatt_is_bda_in_the_srv_chg_clt_list :58-3f-54-73-64-c0
D/bt-att  ( 1601): bda is in the srv chg clt list
D/bt-att  ( 1601): gatt_cleanup_upon_disc 
D/bt-att  ( 1601): exit gatt_cleanup_upon_disc 
D/bt-att  ( 1601): ATT disconnected
I/bt-smp  ( 1601): SMDBG l2c smp_connect_cback 
D/bt-btm  ( 1601): btm_acl_removed
D/bt-btm  ( 1601): btm_bda_to_acl found
D/bt-btm  ( 1601): btm_acl_report_role_change
D/bt-btm  ( 1601): btm_acl_update_busy_level
D/bt-btm  ( 1601): BTM_BLI_ACL_DOWN_EVT
D/bt-btm  ( 1601): acl hci_handle=2 is_le_link=0 connectable_mode=0x0 link_role=1
D/bt-btm  ( 1601): before update p_dev_rec->sec_flags=0xbe
D/bt-btm  ( 1601): Bletooth link down
D/bt-btm  ( 1601): after update p_dev_rec->sec_flags=0xb8
D/bt-btm  ( 1601): btm_acl_resubmit_page
E/bt-btm  ( 1601): btm_sec_disconnected - Clearing Pending flag
I/bt-btm  ( 1601): before Update sec_flags=0xb8
D/bt-btm  ( 1601): btm_ble_update_mode_operation adv_mode = 0
I/bt-btm  ( 1601): after Update sec_flags=0xb8
I/bt-btif ( 1601): bta_jv_free_set_pm_profile_cb(jv_handle: 0x187), idx: 0, app_id: 0xff
D/bt-btm  ( 1601): BTM_ReadRemoteFeatures
D/bt-btm  ( 1601): btm_get_acl_disc_reason_code
E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothRemoteDevices( 1601): Wake lock Aquired
,I/bt-btif ( 1601): HAL bt_hal_cbacks->acl_state_changed_cb
D/BluetoothAdapterService(1111630976)( 1601): Get ACL Connected Devices being called
I/BluetoothAdapterProperties( 1601): Removing device from ACL connected list: 58:3F:54:73:64:C0
,D/BluetoothRemoteDevices( 1601): aclStateChangeCallback: State:DisConnected to Device:58:3F:54:73:64:C0
D/PMS     (  908): acquireWL(4456ce60): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1601 1002 null
,V/BluetoothSapReceiver( 1601): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1601): action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapReceiver( 1601): Calling SAP service start service with action = android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapService( 1601): action: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothSapService( 1601): state: -2147483648
,D/PMS     (  908): acquireWL(44a36160): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1221 10029 null
E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 2856): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 2856): getBluetoothClass(): COD is 5898764
,I/BTConnectionReceiver( 2856): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 2856): Bluetooth Device Name: G3-1
,E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,E/BluetoothDevice( 1221): getBluetoothClass(): COD is 5898764
,D/BluetoothAdapter( 1221): 1114880472: getState(). Returning 12
D/BluetoothAdapterService(1111630976)( 1601): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1601): getBondedDevices: length=10
,D/BluetoothAdapter( 1221): 1114880472: getState(). Returning 12
D/BluetoothAdapterService(1111630976)( 1601): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 1601): getBondedDevices: length=10
D/PMS     (  908): releaseWL(44a36160): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,E/BTIF_CORE( 1601): NETI system_power_manager_wake : 259 param 0
,I/bt-btif ( 1601): HAL bt_hal_cbacks->wake_state_changed_cb
,D/PMS     (  908): releaseWL(4456ce60): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothRemoteDevices( 1601): Wake lock released
,D/PMS     (  908): acquireWL(43d33720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43d33720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1236): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1236): sku_id=99
D/ContactMessageStore( 1236): start background delete task...
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1236): size: 0 , 0
,D/ContactMessageStore( 1236): Background delete complete
,D/PMS     (  908): acquireWL(44a63050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=628975, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44a63050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4389a120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4389a120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4303a068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=688974, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1267): Grow heap (frag case) to 12.766MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(4303a068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44558710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44558710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42fc9750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=748975, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fc9750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42fa8258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42fa8258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/[FDDMI]FDBTService( 4897): Handler(): got msg=2
I/[FDDMI]FDBTService( 4897): receive msg: USER_TIMEOUT
I/[FDDMI]FDBTService( 4897): enter function closeService
V/[FDDMI]FDBTService( 4897): FD bt Service closeService
I/[FDDMI]FDBTService( 4897): enter function stopTimeOut
,I/[FDDMI]FDBTService( 4897): exit function stopTimeOut
,I/[FDDMI]FDBTService( 4897): TimeoutMonitor run
I/[FDDMI]FDBTService( 4897): exit function closeService
I/[FDDMI]FDBTService( 4897): SocketCloseMonitor run
I/[FDDMI]FDBTService( 4897): exit handleMessage
I/[FDDMI]FDBTService( 4897): enter function closeSocket
I/bt-btif ( 1601): BTA_JvDeleteRecord
I/bt-btif ( 1601): BTA_JvRfcommStopServer
D/bt-btm  ( 1601): BTM_FreeSCN 
D/bt-sdp  ( 1601): SDP_DeleteRecord ok, num_records:17
E/bt-btif ( 1601): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1601): BTM_SEC_CLR[20]: id 59
W/System.err( 4897): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/[FDDMI]FDBTService( 4897): FD bt close mServerSocket
I/[FDDMI]FDBTService( 4897): exit function closeSocket
I/[FDDMI]FDBTService( 4897): enter function shutdown
,I/[FDDMI]FDBTService( 4897): exit function shutdown
W/System.err( 4897): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:524)
W/System.err( 4897): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:501)
,W/System.err( 4897): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:398)
W/System.err( 4897): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
W/System.err( 4897): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
W/System.err( 4897): 	at com.futuredial.fdbtserver.g.run(Unknown Source)
E/[FDDMI]FDBTService( 4897): Accept exception: 
I/[FDDMI]FDBTService( 4897): SocketCloseMonitor out
V/[FDDMI]FDBTService( 4897): Handler(): got msg=5006
,I/[FDDMI]FDBTService( 4897): receive msg: MSG_SERVICE_CLOSE
,V/[FDDMI]FDBTService( 4897): successfully stopped  service
I/[FDDMI]FDBTService( 4897): exit handleMessage
,I/[FDDMI]FDBTService( 4897): enter function onDestroy
,I/[FDDMI]FDBTService( 4897): stopForegroundCompat
D/[FDDMI]FDBTService( 4897): isForegroundNeeded:false
,I/[FDDMI]FDBTService( 4897): exit function onDestroy
,D/Process ( 4897): killProcess, pid=4897
,D/Process ( 4897): com.futuredial.fdbtserver.FdbtService.onDestroy:-1 android.app.ActivityThread.handleStopService:3077 android.app.ActivityThread.access$2200:153 
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4897
,I/ActivityManager(  908): Process com.futuredial:FdbtService (pid 4897) has died.
,D/PMS     (  908): acquireWL(445ae4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=808974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(445ae4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(434e2908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(434e2908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44a115f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=868974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44a115f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4387ff08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4387ff08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(432511b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=928974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(432511b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43a8cea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43a8cea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(444290b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=988974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(444290b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4437b108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  908): sending alarm PendingIntent{4260b508: PendingIntentRecord{42d92d48 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784110, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4922 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{42ec4cd8: PendingIntentRecord{42e53bd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452272103066, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{427954b8: PendingIntentRecord{427933a0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452272823470, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{43caa548: PendingIntentRecord{44a56fd8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452272898212, Int=0
,W/ContextImpl( 4535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4535): call getInstance()
,D/SmartSyncUtils( 4535): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4535): MY_DEBUG = false
D/PMS     (  908): releaseWL(4437b108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(44b22838): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4535 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4535): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4535): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4535): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4535): SettingOnTime = 1452319200000, randomSettingOnTime = 1452317662000
,D/SmartSyncScreenOnOffTimeReceiver( 4535): SettingOffTime = 1452304800000, randomSettingOffTime = 1452306743000
,D/SmartSyncScreenOnOffTimeReceiver( 4535): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4535): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4535): bNightModeTurnOffOnce = false
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): releaseWL(44b22838): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4922/10049)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/Process (  908): killProcessQuiet, pid=4647
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4647:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4647
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4462b128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  908): sending alarm PendingIntent{449e2fb8: PendingIntentRecord{42f2deb8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1014178, Int=0
,D/PMS     (  908): acquireWL(4428ad30): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4428ad30): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4462b128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(44b2ef78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1364/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1364/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024130
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024365
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024371
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024388
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024391
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025810
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025822
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360027354
,D/PMS     (  908): releaseWL(44b2ef78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=14 [176][25][1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(449c2bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(449c2bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(445c6e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1048975, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(445c6e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(435f15e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(435f15e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42dac9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1108974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42dac9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44bb8448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44bb8448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4303a4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1168974, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4303a4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44205d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44205d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(445801e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1228974, Int=0
,D/PMS     (  908): releaseWL(445801e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44b1fe60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44b1fe60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43cbb170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1288974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43cbb170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(434d7f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(434d7f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(449fa7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1348974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(449fa7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44592248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44592248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(44a4d720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1408975, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44a4d720): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43d30988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/PMS     (  908): releaseWL(43d30988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/ContextImpl( 4535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3849): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3849): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3849): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3849): Cust_ConnectToPC   : spcsc>false
D/        ( 3849): Cust_ConnectToPC   : IPT>true
D/        ( 3849): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3849): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3849): Index of the first 1 = 3
W/Settings( 3849): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3849): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3849): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3849): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3849): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3849): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42f0d620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(42f0d620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42f2fef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1468974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42f2fef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44627ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44627ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43d335e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/PMS     (  908): releaseWL(43d335e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(44427cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1528975, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44427cb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42fe9650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42fe9650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(443ef688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(443ef688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4416c8c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1588974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4416c8c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43ac0208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43ac0208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43c97348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  908): releaseWL(43c97348): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(44a5dcf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1648974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(44a5dcf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43a86380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43a86380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4399ec28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/PMS     (  908): releaseWL(4399ec28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(438cd198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1708974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1267): Grow heap (frag case) to 12.767MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(438cd198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42f67100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42f67100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42f96c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42f96c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(438c9530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1768974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(438c9530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(42da8b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(42da8b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(445cb028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1828975, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  908): Prepared write state in 31ms
,I/ProcessStatsService(  908): Prepared write state in 25ms
,D/PMS     (  908): releaseWL(445cb028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2016-01-08-02-21-29.bin
,D/PMS     (  908): acquireWL(435c4f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  908): releaseWL(435c4f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4460da38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(4460da38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1561): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1561): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(445706b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42c167c8: PendingIntentRecord{42ac8908 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1888974, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(445706b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4956): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4956): ====startRecUseTime====
D/htc.customization.log.level( 4956):  is 
W/CustomizationLogLevel( 4956): Level value is invalid, use default level 2
D/CustomizationManager( 4956):  Read ACC file spent 0.088 (s)
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4956): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4956): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4956): Parsing tag category name = system
I/CustomizationCIDLoader( 4956): Parsing tag category name = application
I/CustomizationCIDLoader( 4956): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4956): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4956): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4956): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4956): Parsing tag category name = Settings
D/CustomizationManager( 4956):  Read CID file spent 0.132 (s)
D/CustomizationManager( 4956):  All configurations done spent 0.132 (s)
W/HtcNativeFlag( 4956): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4956): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4956): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4956): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4956, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  908): killProcessQuiet, pid=4479
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  908): Killing 4479:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  908): killProcessQuiet, pid=4677
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4661
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Killing 4677:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  908): Killing 4661:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  908):   Force finishing activity ActivityRecord{449d9b80 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  908): Recipient 4661
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4677
W/asset   (  908): Copying FileAsset 0x69c721a8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  908): WIN DEATH: Window{4253fcb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/bt-btif ( 1601): BTA_JvDeleteRecord
D/bt-sdp  ( 1601): SDP_DeleteRecord ok, num_records:16
I/bt-btif ( 1601): BTA_JvRfcommStopServer
E/bt-btif ( 1601): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1601): BTM_SEC_CLR[19]: id 58
D/bt-btm  ( 1601): BTM_FreeSCN 
D/WifiService(  908): Client connection lost with reason: 4
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 4479 uid 10389
W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
W/PackageSettings(  908): Skipping PackageSetting{429d11a8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/SQLiteConnectionPool( 1997): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/Process (  908): killProcessQuiet, pid=4576
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 4576:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1561): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1561): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsRemoved
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  908): Recipient 4576
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  908): Client com.google.android.music (pid 4576): Died!
D/PMS     (  908): acquireWL(44b23bf8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(44b23bf8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1316): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1316): handle notify Blinkfeed plugin client changed
I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4974 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  908): acquireWL(4289b000): PARTIAL_WAKE_LOCK  Icing 0x1 1997 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
W/PackageManager(  908): Unable to load service info ResolveInfo{42f78470 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4974): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4974): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4974): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4974): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4974): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4974): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4974): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4974): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4974): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4974): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4974): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4974): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4974): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4974): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4974): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4974): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4974): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4974): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4974): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4974): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4974): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4974): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4974): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4974): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4974): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4974): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4974): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4974): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4974): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4974): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4974): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4974): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4974): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4974): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4974): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4974): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4974): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4974): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4974): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4974): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4974): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4974): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4974): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4974): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4974): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4974): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4974): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4974): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4974): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4974): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4974): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4974): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4974): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4974): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4974): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4974): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4974): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4974): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4974): threadid=11: thread exiting with uncaught exception (group=0x41fd5e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4974): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4974): Process: com.google.android.apps.docs, PID: 4974
E/AndroidRuntime( 4974): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4974): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4974): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4974): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4974): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4974): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4974): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4974): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4974): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4974): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4974): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4974): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4974): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4974): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4974): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4974): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4974): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4974): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4974): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4974): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4974): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4974): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4974): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4974): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4974): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4974): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4974): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4974): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4974): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4974): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4974): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4974): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4974): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4974): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4974): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4974): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4974): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4974): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4974): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4974): killProcess, pid=4974
D/Process ( 4974): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4992 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Recipient 4974
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4974) has died.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4992): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4992): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4992): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4992): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4992): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4992): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4992): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4992): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4992): threadid=10: thread exiting with uncaught exception (group=0x41fd5e30)
E/AndroidRuntime( 4992): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4992): Process: com.android.keychain, PID: 4992
E/AndroidRuntime( 4992): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4992): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4992): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4992): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4992): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4992): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4992): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4992): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4992): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4992): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5005 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4992): killProcess, pid=4992
D/Process ( 4992): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452273806213.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  908): Recipient 4992
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 4992) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5005): getInstance(Context context)
D/AppTag  ( 5005): getInstance(Context context)
D/AppTag  ( 5005): onCreate()
D/PMS     (  908): acquireWL(4390d7a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3632 10160 null
D/PMS     (  908): releaseWL(4390d7a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4095): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1997): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1997): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1997): Module APK com.google.android.play.games already loaded
I/ActivityManager(  908): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1997): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1997): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1997): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d6f7458
W/dalvikvm( 1997): threadid=49: thread exiting with uncaught exception (group=0x41fd5e30)
I/LocationSettingsChecker( 1997): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1997): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1997): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6d5c06a8
E/DriveAsyncService( 1997): disk I/O error (code 3850)
E/DriveAsyncService( 1997): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1997): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1997): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 1997): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1997): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1997): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 1997): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 1997): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1997): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1997): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1997): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1997): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1997): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1997): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1997): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1997): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1997): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1997): Process: com.google.android.gms, PID: 1997
E/AndroidRuntime( 1997): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1997): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1997): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1997): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1997): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1997): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1997): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1997): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1997): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1997): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1997): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1997): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1997): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1997): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1997): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1997): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1997): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1997): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1997): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 1997): killProcess, pid=1997
D/Process ( 1997): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
I/ActivityManager(  908): Recipient 1997
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.gms (pid 1997) has died.
D/PMS     (  908): handleWLDeath(4289b000): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  908): Client connection lost with reason: 4
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
I/ActivityManager(  908): Resuming delayed broadcast
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20996ms
E/SQLiteLog( 1364): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1364): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63742008
W/dalvikvm( 1364): threadid=1: thread exiting with uncaught exception (group=0x41fd5e30)
E/AndroidRuntime( 1364): FATAL EXCEPTION: main
E/AndroidRuntime( 1364): Process: com.google.process.gapps, PID: 1364
E/AndroidRuntime( 1364): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1364): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1364): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1364): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1364): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1364): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1364): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1364): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1364): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1364): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1364): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1364): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1364): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1364): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1364): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1364): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1364): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1364): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1364): 	... 10 more
E/ActivityManager(  908): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1364): killProcess, pid=1364
D/Process ( 1364): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5033 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5033): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5033 dbg=false s=true
I/DeviceManagement( 5033): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5033): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5033): WorkflowService: Starting workflow service
I/DeviceManagement( 5033): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42438bc0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5033): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5033): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5033): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5033): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  908): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5047 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5033): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5033): SessionStateController: Checking invariants...
I/ActivityManager(  908): Recipient 1364
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.process.gapps (pid 1364) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20775ms

```
